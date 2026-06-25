pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git ''
        }
        stage('Build Docker Image') {
            steps {
                echo 'Docker build -t web-image.'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}