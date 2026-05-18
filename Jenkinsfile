pipeline {
    agent any

    stages {

        stage('Build Docker Containers') {
            steps {
                bat 'docker compose build'
            }
        }

        stage('Start Application') {
            steps {
                bat 'docker compose up -d'
            }
        }

        stage('Check Running Containers') {
            steps {
                bat 'docker ps'
            }
        }
    }
}