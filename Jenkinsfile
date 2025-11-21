pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'git@github.com:irephar/hello-c-jenkins.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                sh 'make'
            }
        }
    }
}

