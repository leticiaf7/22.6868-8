pipeline {
    agent any
    
    stages {
        stage('Testes') {
            steps {
                script {
                    // Seus comandos para construir e rodar os testes
                    sh 'npm install'
                    sh 'npm test'
                }
            }
        }
    }
}
