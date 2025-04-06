pipeline {
    agent { label 'agent' }

    stages {
        stage('Build') {
            steps {
                echo '📦 Installing dependencies...'
                sh 'npm install'
            }
        }
    }
}
