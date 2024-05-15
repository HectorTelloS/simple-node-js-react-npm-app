pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh ' echo npm install' 
            }
        }
         stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}