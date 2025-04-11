pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '🔧 Compilando el proyecto...'
                sh 'echo "Build paso completo"'
            }
        }
        stage('Test') {
            steps {
                echo '✅ Ejecutando tests...'
                sh 'echo "Todos los tests pasaron correctamente"'
            }
        }
        stage('Deploy') {
            steps {
                echo '🚀 Desplegando aplicación...'
                sh 'echo "Aplicación desplegada con éxito"'
            }
        }
    }
}
