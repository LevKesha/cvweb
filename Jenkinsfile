pipeline {
    agent any
    stages {
        stage("one"){
        steps {
        sh 'sudo su - && git pull --rebase https://github.com/LevKesha/cvweb.git'}
        }
        stage('two'){
        steps {
        sh 'docker build .'}
        }
        stage('three'){
        steps {
        sh 'docker run -itd apache'}
    }
}}