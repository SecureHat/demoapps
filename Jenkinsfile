pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. pipeline'
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
                echo 'deployed'
            }
        }
    }
}
