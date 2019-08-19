pipeline {
    agent { dockerfile true }
    stages {
        stage('Build') {
            steps {
                sh 'env'
                sh 'ls -lha $(pwd)'
                sh 'git --version'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "ok"'
            }
        }
    }
}
