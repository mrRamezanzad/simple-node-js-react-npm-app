pipeline {
    agent {
        docker {
            image 'node:20.11.1-alpine'
            args '-p 3000:3000'
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}

