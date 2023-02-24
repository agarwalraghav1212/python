pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'pip i'
            }
        }
        stage('Test') {
            steps {
                sh 'pip start'
            }
        }
    }
}
