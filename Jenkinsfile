pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/ardenhabibullah/simple-node-js-react-npm-app.git'
            }
        }

        stage('Install dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run tests') {
            steps {
                sh 'npm test'
            }
        }

        stage('Build app') {
            steps {
                sh 'npm run build'
            }
        }
    }
}


