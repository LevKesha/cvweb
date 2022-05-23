pipeline {
agent docker
    stages {
        stage('one'){
        steps {
        sh 'cd /var/jenkins_home/workspace/cv'}
        }
        stage('two'){
        steps {
        sh 'docker run -t apache .'}
        }
    }
    }