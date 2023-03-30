pipeline {
    agent { docker { image 'python:3.8.16-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}