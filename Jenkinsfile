pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'python hello.py'
                echo 'Building....'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
