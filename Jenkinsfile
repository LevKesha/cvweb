pipeline {
agent any
    stages {
        stage('one'){
        steps {
        docker build -t apache .
        }
        stage('two'){
        steps {
        echo 'great'}
        }
    }
    }