pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3888:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}g
