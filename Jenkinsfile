pipeline {
    agent {
        docker { image 'debian:buster-slim' }
    }
    stages {
        stage('Build') {
            steps {
                sh 'env'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "ok"'
            }
        }
    }
}
