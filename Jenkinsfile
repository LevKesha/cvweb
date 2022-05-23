pipeline {
agent any
    stages {
        stage('one'){
        steps {
        sh 'start docker'}
        }
        stage('two'){
        steps {
        sh 'docker run -t apache .'}
        }
    }
    }