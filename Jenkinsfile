pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'pp'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}
