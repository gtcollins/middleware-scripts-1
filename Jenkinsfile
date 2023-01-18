pipeline {
    agent any

    stages{
        stage("create zip file"){
            steps{
               
           sh 'zip middlewareScript-${date +%y%m%d-%H%M%S}.zip *  --exclude Jenkinsfile README.md '  
            
            }
        }
        
    }
}
 