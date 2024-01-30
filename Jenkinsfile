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
        stage('curl') {
            steps {
                sh 'sudo curl ident.me'
            }
        }
    }
}
