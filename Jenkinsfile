pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'npm install'
                sh 'npm test'
            }
        }
        #stage('Build Image') {
        #    steps {
        #        sh "docker build -t engineer365/fleashop-server:${env.BUILD_ID} ."
        #        
        #    }
        #}
    }
}
