pipeline {
agent any
    stages {
        stage('one'){
        steps {
        sh 'curl -fsSLO https://get.docker.com/builds/Linux/x86_64/docker-17.04.0-ce.tgz \
  && tar xzvf docker-17.04.0-ce.tgz \
  && rm -r docker/docker-17.04.0-ce.tgz \
  && mv docker/docker /usr/local/bin'}
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