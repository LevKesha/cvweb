pipeline {
    agent any
    stages {
        stage('Build') {
            agent {
                docker {
                    image 'gradle:6.7-jdk11'
                    reuseNode true
                }
            }
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