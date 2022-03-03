pipeline {
    agent any
    stages {
        stage('Clean WS') {
            agent {
                label 'built-in'
            }
            
            steps {
                sh 'echo CLEAN'
                //cleanWs()
            }
        }
        
        stage('run script') {
            steps {
                sh 'pwd'
                sh 'HelloWorld.sh'
            }
        }
    }
}
