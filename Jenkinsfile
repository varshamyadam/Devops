pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/varshamyadam/Devops.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test Case Execution') {
            steps {
                echo 'Test Case Executing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}