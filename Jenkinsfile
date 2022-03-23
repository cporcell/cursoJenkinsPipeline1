// Declarativa: Es más cómoda.. más guiada, menos flexible (practicamente lo que se hace en Jenkins)
pipeline {
    stages {
        stage('Compilacion') {
            steps {
                echo 'Voy a compilar:'
                echo 'Estoy en ello ...'
                echo 'Listo'
                
            }
            post {
                success {
                    echo 'Se ejecuta solo si los steps han ido bien'
                }
                failure {
                    echo 'Se ejecuta solo si los steps han ido mal'
                }
                always {
                    echo 'Se ejecuta en cualquier caso'
                }
            }
        }
        stage('pruebas') {
            steps {
                echo 'Voy a probar:'
                echo 'Estoy en ello ...'
                echo 'Listo'
                
            }
            post {
                success {
                    echo 'Se ejecuta solo si los steps han ido bien'
                }
                failure {
                    echo 'Se ejecuta solo si los steps han ido mal'
                }
                always {
                    echo 'Se ejecuta en cualquier caso'
                }
            }
        }
    }
    post {
        success {
            echo 'Se ejecuta solo si los steps han ido bien'
        }
        failure {
            echo 'Se ejecuta solo si los steps han ido mal'
            }
            }
}



// Scripted: Más potente, mas flexible, menos cómoda. (La buena, pero exige más nivel para utilizarlas)