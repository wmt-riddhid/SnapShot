pipeline {
    agent {
        any {
            image 'node:6-alpine'
            args '-p 3005:3000'
        }
    }
     environment {
        CI = 'true' 
    }
    stages {
        stage('Build') {
            steps {
                sh '/usr/bin/npm install'
            }
        }
    }
}