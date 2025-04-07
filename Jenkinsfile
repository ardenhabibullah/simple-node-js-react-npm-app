pipeline {
    agent { label 'docker-ssh-jenkins-agent' }

    stages {
        stage('Build') {
            steps {
                echo 'Running build step...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running test step...'
            }
        }

        stage('Deliver') {
            steps {
                echo 'Running deliver step...'
            }
        }
    }
}
