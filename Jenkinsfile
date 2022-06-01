pipeline {
     agent { label 'apache' }
    stages {
        stage("one"){
        steps {
        sh 'git pull --rebase https://github.com/LevKesha/cvweb.git'}
        }
        stage('two'){
        steps {
        sh 'sudo apt-get install docker'}
        }
        stage('three'){
        steps {
        sh 'docker run -itd apache'}
    }
}}