pipeline {
    agent any

    stages {
        stage('Checkout' {
            steps {
                echo 'Récupération du code...'
            }
        }

        stage('Test') {
            steps {
                echo 'Exécution des tests...'
            }
        }

        stage('Build') {
            steps {
                echo 'Build de l’application...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline terminé avec succès ✅'
        }
        failure {
            echo 'Pipeline échoué ❌'
        }
        always {
            echo 'Nettoyage terminé.'
        }
    }
}
