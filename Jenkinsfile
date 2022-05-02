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
               sh 'docker login -u lakshit45 -p jesuschrist@11'
               sh 'docker build -t lakshit45/iiii .
               sh ' docker push lakshit45/iiii '
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
