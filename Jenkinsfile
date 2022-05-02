pipeline {
    agent any

    stages {
        stage('npm install') {
            steps {
               sh 'npm install'
            }
        }
        
        stage('npm server') {
            steps {
              script {
               sh 'docker login u lakshit45 -p jesuschrist@11'
              }
            }
        }
        stage('npm ') {
            steps {
               sh 'node index.js'
            }
        }
   }
}
