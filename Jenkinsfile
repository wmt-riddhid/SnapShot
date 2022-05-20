pipeline{
    agent{
        any{
            image 'node:16.14.2'
        }
    }
}
    stages{
        stage('Build'){
            steps{
                sh 'npm install'
            }
        }
    }
}