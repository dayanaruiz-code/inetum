//Pipeline declarativo
pipeline{
    //Ejecutar desde cualquier agente(nodo) disponible 
    agent any
    
    //Fases
    stages{
        stage ('Build'){
            //Pasos de la fase
            steps{
                echo "Building artifact..."
            }
        }
        stage ('Fase2 - Testing'){
            //Pasos de la fase
            steps{
                echo "Test unitarios..."
                echo "Test Integración..."
                echo "Test Aceptación..."
            }
        }
        stage (' Deploy'){
            //Pasos de la fase
            steps{
                echo "Deploy artifact.."
            }
        }
    }
}
