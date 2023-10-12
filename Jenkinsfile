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
            	 sh 'npm config set unsafe-perm true'
                sh 'npm install --save'
            }
        }
    }
  }
