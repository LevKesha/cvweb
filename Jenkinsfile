pipeline {
agent any
    stages {
        stage('one'){
        steps {
        sh 'git pull --rebase https://github.com/LevKesha/cvweb.git'}
        }
        stage('two'){
        steps {
        echo 'docker build -t apache .'}
        }
        stage('three'){
        steps {
        echo 'success'}
    }
}}