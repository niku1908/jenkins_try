pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning the repo...'
                git branch: 'main', url: 'https://github.com/niku1908/jenkins_try.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add your build logic here
            }
        }

        stage('Test') {
            steps {
                echo 'Running Tests...'
                // Add your test steps here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // Add your deployment logic here
            }
        }
    }

    post {
        always {
            echo 'This will always run after the stages complete'
        }
    }
}
