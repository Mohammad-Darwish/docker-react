pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout source code from your repository
                // git 'https://github.com/your/repository.git'
                sh 'ls -l'
            }
        }

        stage('Build') {
            steps {
                // Install dependencies and build JavaScript code
                sh 'npm install'
                sh 'npm run build'
            }
        }

        // stage('Test') {
        //     steps {
                // Run tests for your JavaScript code
                // sh 'npm run test'
            // }
        // }

        // stage('Deploy') {
        //     steps {
                // Deploy your JavaScript code to a server or cloud platform
                // sh 'npm run deploy'
            // }
        // }
    }
}
