pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'cd ${JENKINS_HOME}/workshop/jkl'
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
