pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm install' // Si estás usando Node.js
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'npm test' // Si tienes pruebas configuradas
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Aquí colocas los comandos de despliegue
            }
        }
    }
}
