pipeline {
    agent {
        docker {
            image 'node:16' // Use Node 16 Docker image
            args '-p 3000:3000'
        }
    }
    
    stages {
        stage('Build') {
            steps {
                sh 'npm install --save'
            }
        }
    }
   }
