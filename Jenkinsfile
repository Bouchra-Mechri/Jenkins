pipeline {
    agent any

    triggers {
        pollSCM('* * * * *')
    }

    stages {
        stage('Checkout') {
            steps {
                echo "Récupération du code source"
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo "Build du projet"
                // Ajoutez les commandes de build ici
            }
        }

        // stage('Execute') {
        //     steps {
        //         sh "node.js"
        //         // Ajoutez les commandes de build ici
        //     }
        // }
    }
}
