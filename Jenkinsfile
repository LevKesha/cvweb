pipeline {
agent any
    stages {
        stage('one'){
        steps {
        sh 'apt-get install docker'}
        }
        stage('two'){
        steps {
        sh 'docker build -t apache .'}
        }
    }
    }