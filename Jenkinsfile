pipeline {
    agent any

    environment { 
        MASTER = 'Master Jenkins'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building main..${env.MASTER}'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing main..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying main....'
            }
        }
    }
}