pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'npm install' // Ejecuta npm install en la raíz del repositorio
            }
        }
        stage('Test') {
            steps {
                bat 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
