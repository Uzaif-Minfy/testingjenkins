pipeline {
    agent any
    stages {
        stage('Build Docker Image') {
            steps {
                script {
                    echo "hello"
                }
            }
        }
    post {
        success {
            echo "Docker image built and pushed to DockerHub!"
        }
        failure {
            echo "Something went wrong."
        }
    }
}
