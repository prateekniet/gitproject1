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
