pipeline {
     agent { label 'apache' }
    stages {
        stage("one"){
        steps {
        sh 'git pull --rebase https://github.com/LevKesha/cvweb.git'}
        }
        stage('two'){
        steps {
        sh 'docker build -t apache .'}
        }
        stage('three'){
        steps {
        sh 'docker run -itd apache'}
    }
}}