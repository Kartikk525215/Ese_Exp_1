pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building Portfolio Website…"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy step will go here…"
            }
        }
    }
}
