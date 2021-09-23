pipeline{
    agent any
    tools{
        NodeJS "node"
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