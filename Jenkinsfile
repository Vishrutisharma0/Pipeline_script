pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                bat 'build.bat'
            }
        }
        stage('Unit Test') {
            steps {
                bat 'test.bat'
            }
        }
              stage('Quality') {
            steps {
                bat 'quality.bat'
            }
        }
        stage('Deploy') {
            steps {
                bat 'deploy.bat'
            }
        }
    }
}
