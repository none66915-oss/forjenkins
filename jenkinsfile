pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/none66915-oss/forjenkins.git'
            }
        }
        stage('Compile') {
            steps {
                sh 'javac helloworld.java'
            }
        }
        stage('Execute') {
            steps {
                sh 'java helloworld'
            }
        }
    }
}

