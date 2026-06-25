pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                echo 'Docker build -t web-image-app .'
            }
        }

        stage('Run Docker Container') {
            steps {
                echo 'Docker run -d -p 8081:80 web-image-app'
            }
        }
    }
}