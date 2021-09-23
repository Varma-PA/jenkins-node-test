pipeline{
    agent any
    tools{
        nodejs "node"
    }
    stages{
        stage('Check Node'){
            steps{
                echo 'Checking Node JS'
                echo %PATH%
                sh 'npm config list'
            }
        }
    }
}