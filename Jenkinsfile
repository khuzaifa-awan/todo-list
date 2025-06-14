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

        stage('Deploy') {
            steps {
                echo 'Deploying to /var/www/html/'
                sh 'sudo rm -rf /var/www/html/*'
                sh 'sudo cp -r * /var/www/html/'
            }
        }
    }
}
