pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                sh 'docker build -t app .'
            }
        }
        stage('Test'){
            steps{
                echo 'TEST'
                sh '/bin/nc -vz localhost 22'
            }
        }
        stage('Deploy'){
            steps{
                echo 'DEPLOY'
            }
        }
    }
}