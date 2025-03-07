pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/kondareddypp/todo-list-app.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'npm install'
                sh 'npm run build'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add your deployment steps here, for example, deploying to a server or cloud
            }
        }
    }
}
