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
            agent {
                label 'built-in'
            }
            steps {
                sh 'ls'
                sh './HelloWorld.sh'
            }
        }
    }
}
