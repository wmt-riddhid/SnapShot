pipeline {
    agent {
        docker {
            image 'node:6-alpine'
            arge '-p3000:3000'
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