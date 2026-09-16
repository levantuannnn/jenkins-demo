pipeline {
    agent any

    stages {

        stage('Check Environment') {
            steps {
                sh 'uname -a'
                sh 'python3 --version'
            }
        }

        stage('Test') {
            steps {
                sh 'python3 -m pytest'
            }
        }
    }
}