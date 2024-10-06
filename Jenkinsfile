pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/niku1908/jenkins_try.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
                // Add build steps here
            }
        }

        stage('Test') {
            steps {
                echo 'Running Tests...'
                // Add test steps here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deploy steps here
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished'
        }
    }
}
