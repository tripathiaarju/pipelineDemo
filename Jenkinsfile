pipeline {
    agent any
 
    stages {
        stage('Checking Version') {
            steps {
                sh 'javac -version'
            }
        }
        stage('Compiling') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }

        stage('Running') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
