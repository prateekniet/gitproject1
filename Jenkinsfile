pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "🔨 Running BUILD stage"
                sh '''
                    echo "Compiling source code..."
                    sleep 2
                    echo "Build completed!"
                '''
            }
        }

        stage('Test') {
            steps {
                echo " Testing"
                sh '''
                    echo "Testing 1st usecase"
                    sleep 2
                    echo "All tests passed!"
                '''
            }
        }

        stage('Deploy') {
            steps {
                echo "Running DEPLOY stage"
                sh '''
                    echo "Deploying application..."
                    sleep 2
                    echo "Deployment successful!"
                '''
            }
        }
    }
}
