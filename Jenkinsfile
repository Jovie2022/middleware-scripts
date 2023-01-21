pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
               
           sh 'yum install zip, zip middlewareScript-${BUILD_NUMBER}.zip * --exclude Jenkinsfile README.md' 
            
            }
        }
        
    }
}