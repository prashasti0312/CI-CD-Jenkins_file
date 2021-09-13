pipeline {
    agent any
    environment {
        DD_GIT_DEFAULT_BRANCH = 'main'
    }
    stages {
        stage('Build') {
            steps {
                echo "Hello! This is build stage"
            }
        }
        stage('Test') {
            steps {
                echo "This is test stage"
            }
        }
    }
