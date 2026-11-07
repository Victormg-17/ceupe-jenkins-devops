
pipeline {
    agent any

    stages {
        stage('Preparacion') {
            steps {
                echo 'Obteniendo codigo desde GitHub'
            }
        }

        stage('Construccion') {
            steps {
                echo 'Preparando la aplicacion'
            }
        }

        stage('Pruebas') {
            steps {
                echo 'Ejecutando validaciones'
            }
        }

        stage('Despliegue') {
            steps {
                echo 'Simulando despliegue'
            }
        }
    }

    post {
        success {
            echo 'Integracion Jenkins y GitHub exitosa'
        }
    }
}
