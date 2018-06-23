pipeline {
    agent any

    stages {
        stage('Clean') {
            withMaven(maven : 'maven'){
                  sh 'mvn clean'
            }   
            
        }
        
    }
}
