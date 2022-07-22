@Library ("Libreria_compartida") _
pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
               script {
                Libreria_compartida.mostrar (
               Hola: 'echo "Hello"',
               Esesto: 'echo "Que es esto"' )
               }
            }  
        }

stage('Chao') {
            steps {
                script{
                    Libreria_compartida.otracosa (
                        Adios: 'echo "haciendo ping"'
                    )
                }
        
    }
}
    }

}

