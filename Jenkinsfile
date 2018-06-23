pipeline {
    agent any

    stages {
        stage('Clean') {
            steps{
            withMaven(maven : 'maven'){
                  sh 'mvn clean'
            }   
            
            }     
            
        }
        
    }
}
