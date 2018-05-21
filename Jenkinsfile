pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'java Hello.java'
            }
        }
        stage('Test') {
            steps {
                sh 'javac Hello'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
