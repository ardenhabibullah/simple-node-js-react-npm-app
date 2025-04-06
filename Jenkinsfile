pipeline {
    agent { label 'docker-ssh-jenkins-agent' }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
