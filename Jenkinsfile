pipeline {
    agent any
    
    tools {
        // This name MUST match the name you gave it in 'Manage Jenkins -> Tools'
        jdk 'name' 
    }

    stages {
        stage('Compile') {
            steps {
                // Now 'javac' will be found because Jenkins adds it to the PATH
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
