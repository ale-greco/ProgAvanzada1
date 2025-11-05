pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/ale-greco/ProgAvanzada1.git'
            }
        }
        stage('Build') {
            steps {
                bat "Saludo.bat"
                echo "Estoy en jenkinsfile"
            }
        }
    }
}
