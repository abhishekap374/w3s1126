pipeline{
    agent any
    stages{
        stage("Git Checkout"){
            steps{
                git credentialsId: 'forGitconfigure', url: 'https://github.com/abhishekap374/w3s1126.git'
            }
        }
    }
}
