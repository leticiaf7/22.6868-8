pipeline {
    agent any
    
    stages {
        stage('Testes') {
            steps {
                script {
                    sh 'node --version'
                    sh 'npm install'
                    sh 'npm test'
                }
            }
        }
    }
}
