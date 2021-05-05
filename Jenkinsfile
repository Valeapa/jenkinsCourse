// Pipeline declarativo
pipeline {
    
    // Ejecutar desde cualquier agente (nodo) disponible
    agent any
    
    // Fases (stages)
    stages {
        
        stage('Build') {
            // Pasos de la fase
            steps {
                echo "Building artifact"
            }
        }
        
        stage('Testing') {
            // Pasos de la fase
            steps {
                echo "Test unitarios..."
                echo "Test integración..."
                echo "Test aceptación..."
            }
        }
        
        stage('Deploy') {
            // Pasos de la fase
            steps {
                echo "Deploying artifact"
            }
        }
    }
}
