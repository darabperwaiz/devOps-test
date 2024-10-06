pipeline {
    agent any
    stages {
        stage('Install Dependencies') { 
            steps {
                bat 'npm install'
            }
        }
        stage('Run Server') { 
            steps {
                bat 'node server.js'
            }
        }
    }
}