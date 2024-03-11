pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'bash build.sh'
            }
        }
        stage('Unit Test') {
            steps {
                sh 'bash test.sh'
            }
        }
              stage('Quality') {
            steps {
                sh 'bash quality.sh'
            }
        }
        stage('Deploy') {
            steps {
                sh 'bash deploy.sh'
            }
        }
    }
}
