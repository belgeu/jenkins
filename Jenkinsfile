pipeline {
    agent any
    stages {
        stage('test') {
            steps {
                sh 'python --version'
                sh 'env'
            }
        }
        stage('test1') {
            steps {
                sh 'python --version'
            }
            steps {
                sh 'pwd'
            }
        }
        stage('test2') {
            steps {
                sh 'python --version'
            }
            steps {
                sh 'whoami'
            }
            steps {
                sh 'id'
            }
        }
    }
}
