pipeline {
    agent { docker {}}
    stages {
        stage('build') {
            steps {
                sh 'echo Build stage'
            }
        }
        stage('test') {
            steps {
                sh 'echo Test stage'
            }
        }
    }
}