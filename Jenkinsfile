pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'yarn' 
            }
        }
         stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }
    }
}