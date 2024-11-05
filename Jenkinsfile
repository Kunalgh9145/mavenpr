pipeline {
    agent any  // Run on any available Jenkins agent

    stages {
        stage('Build') {
            steps {
                // Compile and package the Maven project
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                // Run tests
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                // Placeholder for deployment (add your specific deployment steps here)
                echo 'Deploying application...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed.'
        }
    }
}
