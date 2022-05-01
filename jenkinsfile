pipeline{
    agent any
   
    stages{
        stage("npm install"){
            steps{
                sh  ' npm install '
            }
        }
            stage("project-maven-build"){
            steps{
               sh 'node index.js'

            }
        }
            
    }
