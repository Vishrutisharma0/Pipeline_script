pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'build.sh'
            }
        }
        stage('Unit Test') {
            steps {
                sh 'test.sh'
            }
        }
              stage('Quality') {
            steps {
                sh 'quality.sh'
            }
        }
        stage('Deploy') {
            steps {
                sh 'deploy.sh'
            }
        }
    }
}
