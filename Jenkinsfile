pipeline {
    agent any
    
    stages {
        stage('Print ENVs') {
            steps {
                sh 'printenv'
            }
        }
        stage('Git Version') {
            steps {
                sh 'git --version'
            }
        }
        stage('install Docker') {
            steps {
                sh 'sudo yum install docker'
            }
        }
    }
}
