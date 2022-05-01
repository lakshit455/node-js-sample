pipeline{
    agent any
    tools 

    stages{
        stage("project-maven-test"){
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

    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}
