pipeline {
    agent any
    stages {
        stage('Clean WS') {
            agent {
                label 'built-in'
            }
            
            steps {
                cleanWs()
            }
        }
        
        stage('run script') {
            steps {
                sh 'pwd'
            }
        }
    }
}
