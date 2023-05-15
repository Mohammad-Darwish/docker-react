pipeline {
    agent { docker { image 'node:18.16.0-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
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
