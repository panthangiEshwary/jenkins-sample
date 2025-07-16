pipeline {
    agent any  // Run on any available agent/node

        stage('Clone') {
    steps {
        echo '📥 Cloning Repository...'
        git url: 'https://github.com/panthangiEshwary/jenkins-sample.git', branch: 'main'
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
