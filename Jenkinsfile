Spipeline {
    agent { label 'docker-ssh-jenkins-agent' }

    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }

        stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }

        stage('Deploy') {
            steps {
                sh './kill.sh'
                sh './deliver.sh'
            }
        }
    }
}
