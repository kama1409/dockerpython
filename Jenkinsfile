pipeline {
    agent { docker { image 'dpckerpython:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
