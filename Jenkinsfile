pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                bat 'npm install'  // Cambiado para Windows
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                bat 'npm test'     // Cambiado para Windows
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Agrega aquí los comandos de despliegue si es necesario, usando "bat"
            }
        }
    }
}
