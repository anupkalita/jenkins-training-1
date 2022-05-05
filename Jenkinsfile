pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                git url: 'https://github.com/anupkalita/jenkins-training-1.git', branch: 'master'
            }
        }

        stage('Build'){
            steps{
                java Simple.java
            }
        }
    }
}