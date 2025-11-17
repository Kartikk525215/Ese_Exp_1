pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Kartikk525215/Ese_Exp_1.git'
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
