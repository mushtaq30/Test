pipeline {
    agent any
    environment{
        New_Version= 0.001
        SERVER_CREDENTIALS = credential('server-credentials')
    }
    stages{
        stage('build') {
            echo "Building application"
        }
        stage('Test') {
            echo "Testing application"
        }
        stage('Package') {
            echo "Packaging application"
        }
    }
}