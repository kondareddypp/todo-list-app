pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/kondareddypp/todo-list-app.git'
            }
        }

        stage('Build') {
            steps {
                // Add build steps here (e.g., npm install, npm run build)
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                // Add test steps here (e.g., npm test)
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                // Add deployment steps here
                echo 'Deploying the application...'
            }
        }
    }
}

