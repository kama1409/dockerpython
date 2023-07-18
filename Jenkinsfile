pipeline {
    agent { docker { image 'dpckerpython:latest' } }
    args '-e DOCKER_OPTS="--dns 8.8.8.8"'
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
