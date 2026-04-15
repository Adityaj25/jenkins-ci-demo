pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Adityaj25/jenkins-ci-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'No build required for Python project'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage executed successfully'
            }
        }
    }
}
