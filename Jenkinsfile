pipeline {
agent any
    stages {
        stage('one'){
        steps {
        sh 'docker --version'}
        }
        stage('two'){
        steps {
        sh 'docker build -t apache .'}
        }
        stage('three'){
        steps {
        echo 'great'}
    }
}}