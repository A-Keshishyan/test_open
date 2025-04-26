pipeline {
    agent any

    stages {
        stage('Check Python') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Run Python Script') {
            steps {
                sh 'python3 test.py'
            }
        }
    }
}
