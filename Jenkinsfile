pipeline{
    agent any
    tools{
        nodejs "node"
    }
    stages{
        stage('Check Node'){
            steps{
                echo 'Checking Node JS'
                bat 'node --version'
                bat 'npm --version'
            }
        }

        stage('Cloning Git'){
            steps{
                echo 'Cloning Git'
                git branch: 'main', url: 'https://github.com/Varma-PA/jenkins-node-test'
            }
        }

        stage('Running Main Index file'){
            steps{
                echo 'Running Index file'
                bat 'node index.js'
                echo 'Completed'
            }
        }

    }
}