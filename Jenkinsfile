pipeline{
    agent any
    tools{
        nodejs "NodeJS"
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