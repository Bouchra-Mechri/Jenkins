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

//stage('Execute') {
//steps {
//sh "node.js"  sh dans un pipeline Jenkins est utilisée pour exécuter des commandes shell ou des scripts shell dans l'environnement de construction. ken ala windows nst3mlou bat 
// Ajoutez les commandes de build ici

//}
//}


 }