pipeline {
    agent any
    stages {
        stage('Build Java') {
            steps {
                sh 'javac Hello.java'
                sh 'java Hello'
            }
        }
    }
}
