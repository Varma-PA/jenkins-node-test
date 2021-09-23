pipeline{
    agent any
    tools{
        NodeJs "node"
    }
    stages{
        stage('Check Node'){
            steps{
                echo 'Checking Node JS'
                sh 'node --version'
            }
        }
    }
}