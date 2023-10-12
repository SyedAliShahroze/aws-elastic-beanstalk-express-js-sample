pipeline {
    agent {
        docker {
            image 'node:16' // Use Node 16 Docker image
            reuseNode true
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
