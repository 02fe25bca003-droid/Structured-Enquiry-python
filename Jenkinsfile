
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Check Python') {
            steps {
                sh 'python3 --version'
            }
        }

        stage('Verify Project Files') {
            steps {
                sh 'pwd'
                sh 'ls -la'
            }
        }
    }
}
