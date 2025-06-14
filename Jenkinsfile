pipeline {
    agent any

    stages {
        stage('Pull Code') {
            steps {
                echo 'Cloning the repository...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'No build needed for static HTML/CSS/JS.'
            }
        }

        stage('Test') {
            steps {
                echo 'No automated tests provided.'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Ready to deploy to EC2 server.'
            }
        }
    }
}
