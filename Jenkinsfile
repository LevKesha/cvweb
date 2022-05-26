pipeline {
    agent {
        docker { image 'docker:16.13.1-alpine' }
    }
    stages {
        stage('one'){
        steps {
        sh 'git pull --rebase https://github.com/LevKesha/cvweb.git'}
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