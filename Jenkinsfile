pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'cd ${JENKINS_HOME}/workspace/jkl'
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
