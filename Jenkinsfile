pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                bat 'docker --version'
            }
        }
        stage('Build Docker Image') {
            steps {
                bat 'docker build -t uadb-dev:1.0 .'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}