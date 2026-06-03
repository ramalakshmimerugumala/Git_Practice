pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'gcc file1.c -o app'
            }
        }

        stage('Test') {
            steps {
                sh './app'
            }
        }
    }
}
