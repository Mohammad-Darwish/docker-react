pipeline {
    agent any

    tools {
        nodejs '20.2.0'
    }

    stages {
        stage('Checkout') {
            steps {
                // Checkout source code from your repository
                // git 'https://github.com/your/repository.git'
                sh 'ls -l'
                sh 'docker --version'
            }
        }

        stage('Build') {
            steps {
                sh 'docker build -t mohammad/docker-react -f Dockerfile.dev .'
            }
        }
    }
    post {
        always {
            echo 'One way or another, I have finished'
            deleteDir() /* clean up our workspace */
        }
    }
}
