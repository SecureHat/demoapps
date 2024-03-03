pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. pipeline'
                echo 'built changes'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'whoami'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh 'date'
            }
        }
    }
}
