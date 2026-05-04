pipeline {
    agent any
    stages {
        // The 'Checkout' stage is handled automatically by Jenkins
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
