pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'cd ${JENKINS_HOME}/workspace/jkl'
                sh 'javac Hello.java'
            }
        }
        stage('Test') {
            steps {
                sh 'java Hello'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
