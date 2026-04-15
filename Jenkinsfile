pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                echo 'Cloning code...'
            }
        }



        stage('Builds') {
            steps {
                sh 'npm install invalid-package-xyz'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
