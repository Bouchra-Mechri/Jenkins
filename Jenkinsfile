pipeline {
agent any
triggers {
pollSCM('* * * * *') // Vérifier git kol d9i9a
}
stages {

stage('Checkout') { // yverifi kol mara chnowa sar fi git 
steps {
echo "Récupération du code source"
checkout scm  //utilisée dans les configurations de pipeline Jenkins, en particulier avec des systèmes de gestion de versions tels que Git
}
}


stage('Build') {
steps {
echo "Build du projet"

// Ajoutez les commandes de build ici

}
}


stage('Execute') {
steps {
sh "node.js"

// Ajoutez les commandes de build ici

}
}


 }