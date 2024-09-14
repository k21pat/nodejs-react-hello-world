/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'node:20.17.0-alpine3.20' } }
    stages {
        stage('init') {
            steps {
                sh 'node --version'
            }
        }
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
