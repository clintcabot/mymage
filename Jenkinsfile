pipeline {
    agent { dockerfile { dir 'build' } }
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
