pipeline {
    agent { docker { image 'python:3.8.10-alpine'}}
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