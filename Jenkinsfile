pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Building the project 3"'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests 3"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying the project 3"'
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded! 3'
        }
        failure {
            echo 'Pipeline failed! 3'
        }
    }
}
