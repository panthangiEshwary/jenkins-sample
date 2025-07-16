pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo '📥 Cloning Repository...'
                git 'https://github.com/panthangiEshwary/jenkins-sample.git'
            }
        }

        stage('Build') {
            steps {
                echo '🔧 Running build step...'
                sh 'echo "Build Successful!"'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Running tests...'
                sh 'echo "Tests passed!"'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Deploying Application...'
                sh 'echo "Deployed successfully!"'
            }
        }
    }
}
