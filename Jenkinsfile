@Library ("Libreria_compartida") _
pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
               script {
                variables.mostrar (
               Hola: 'echo "Hello"'
               Esesto: 'echo "Que es esto"' )
               }
            }  
        }

stage('Chao') {
            steps {
                script{
                    variables.mostrar(
                        Adios: 'echo "haciendo ping"'
                    )
                }
        
    }
}
    }

}

