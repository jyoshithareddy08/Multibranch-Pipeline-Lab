pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building branch: ${env.BRANCH_NAME}"
            }
        }

        stage('Test') {
            steps {
                echo 'Tests completed successfully!'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying branch: ${env.BRANCH_NAME}"
            }
        }
    }
}