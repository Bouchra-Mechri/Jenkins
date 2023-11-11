pipeline {
    agent any //agent machine virtuelle machine physique 

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
        stage("clear")  //nzid stage bch n9ra variable d'environ
        {
            steps {
                echo "Build ID : ${env.BUILD_ID}"
            }
        }
    }
}
