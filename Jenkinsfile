pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
                git url: 'https://github.com/jagannathwakle/heel.git', branch: 'master'
            }
        }
        stage('Deploy') {
            steps {
                sh 'cp * /var/www/html/'
            }
        }
    }
}
