pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Install dependencies
                sh 'npm install'
            }
        }
        
        stage('Test') {
            steps {
                // Run tests
                sh 'npm test'
            }
        }
        
        stage('Deploy') {
            steps {
                // Perform deployment steps
                // For example, copy files to a remote server, start the application, etc.
                sh 'npm run deploy'
            }
        }
    }
}
