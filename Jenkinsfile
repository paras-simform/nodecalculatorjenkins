pipeline {
    agent { docker { image 'node:10.9' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}