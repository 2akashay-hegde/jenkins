pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/2akashay-hegde/jenkins.git'
        }
        stage('Build Docker Image') {
            steps {
                echo 'Docker build -t web-image-app.'
            }
        }
        stage('Run Docker Container') {
            steps {
                echo 'Docker run -d -p 8081:81 web-image-app'
            }
        }
    }
}