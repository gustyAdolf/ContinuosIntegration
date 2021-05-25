// Pipeline declarativo
pipeline {
    
    // 1. Ejecutar cualquier nodo
    agent any
    
    stages {
        
        stage("Build") {

            // Pasos (ejecutables dependiendo de la condicion anterior)
            steps {
                
                echo "Building artifact"
                
            }
        }
      
      stage("Testing") {
        steps {
          echo "Test.."
        }
    }
    
  }
}
