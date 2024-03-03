pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. pipeline'
                sh 'cat /etc/hosts'
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
