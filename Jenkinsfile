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
               sh "chmod +x -R ${env.WORKSPACE}"
                sh './jenkins/test.sh'
            }
        }
    }
}