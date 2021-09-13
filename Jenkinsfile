pipeline {
    agent any
    environment {
        DD_GIT_DEFAULT_BRANCH = 'main'
    }
    stages {
        stage('Build') {
            steps {
                echo "Hello! This is build stage"
                mkdir newdir
                cd newdir
                vi info.txt
            }
        }
        stage('Test') {
            steps {
                echo "This is test stage"
                test -f info.txt
            }
        }
    }
}
