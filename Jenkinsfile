pipeline{
    agent any
    
    environment {
    PATH = "/opt/maven3/bin:$PATH"
    }
    stages{
        stage("Git Checkout"){
            steps{
                git credentialsId: 'forGitconfigure', url: 'https://github.com/abhishekap374/w3s1126.git'
            }
        }
        stage("Maven Build"){
            steps{
                sh "mvn clean package"
            }
        }
    }
}
