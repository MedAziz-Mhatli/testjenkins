pipeline {
    agent any

    stages {
        stage('Récupération du code source') {
            steps {
                // Récupérer le code source depuis le référentiel Git
                checkout scm
            }
        }

        stage('Affichage de la date système') {
            steps {
                sh 'date' // Exécuter la commande 'date' pour afficher la date système
            }
        }
    }
}
