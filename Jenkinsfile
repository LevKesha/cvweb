pipeline {
agent any
    stages {
        stage('one'){
        steps {
        sh 'docker build -t apache .'}
        }
        stage('two'){
        steps {
        echo 'great'}
        }
    }
    }