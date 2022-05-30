pipeline {
    agent any
    stages {
        stage("one"){
        steps {
        sh 'git pull --rebase https://github.com/LevKesha/cvweb.git'}
        }
        stage('two'){
        steps {
        sh 'docker ps -a'}
        }
        stage('three'){
        steps {
        sh 'docker run -itd apache'}
    }
}}