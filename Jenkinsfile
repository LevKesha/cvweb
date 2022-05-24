pipeline {
agent any
    stages {
        stage('one'){
        steps {
        sh 'rm -r /var/lib/apt/lists/lock'}
        }
        stage('two'){
        steps {
        echo 'apt-get install sudo'}
        }
    }
    }