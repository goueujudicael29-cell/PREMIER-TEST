pipeline {
    agent any

    stages {
        stage('Récupération du code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/goueujudicael29-cell/PREMIER-TEST.git'
            }
        }

        stage('Affichage de la date système') {
            steps {
                sh 'date'
            }
        }
    }
}