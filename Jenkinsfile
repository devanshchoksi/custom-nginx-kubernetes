pipeline{
    agent any
    stages{
        stage('git clone'){
            steps{
                sh "git clone https://github.com/devanshchoksi/custom-nginx-kubernetes.git"
                sh "rm -rf custom-nginx-kubernetes"
            }
        }
    }
}