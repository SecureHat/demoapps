pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build'
                sh 'whoami'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh 'date'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh 'pwd'
            }
        }
    }
}
