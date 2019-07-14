pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                sh 'Docker build -t app .'
            }
        }
        stage('Test'){
            steps{
                echo 'TEST'
            }
        }
        stage('Deploy'){
            steps{
                echo 'DEPLOY'
            }
        }
    }
}