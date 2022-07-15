pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Build stage'
            }
        }
        stage('run') {
            steps {
                python main.py
            }
        }
        stage('test') {
            steps {
                echo 'Test stage'
            }
        }
    }
}