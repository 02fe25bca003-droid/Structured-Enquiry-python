
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Repository checked out by Jenkins'
            }
        }

        stage('Check Python') {
            steps {
                bat 'python --version'
            }
        }

        stage('Verify Project Files') {
            steps {
                bat 'echo Current workspace:'
                bat 'cd'
                bat 'dir'
            }
        }
    }
}

