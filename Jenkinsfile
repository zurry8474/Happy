pipeline {
    agent any
    
    stages {
    
         stage('run backend') {
         
             steps {
             
                   echo 'executing gradle'
                 
                   withGradle() {
                       sh './gradlew'
                   
                   }
             }
         }
         
          stage('build') {
         
             steps {
             
                   echo 'building the app' 
             }
         }
        
          stage('tests') {
         
             steps {
             
                   echo 'testing the app' 
             }
         }
         
         
          stage('deploying') {
         
             steps {
             
                   echo 'deploying the app' 
             }
         }
         
          stage('checkout') {
         
             steps {
             
                   echo 'checkout the app' 
             }
         }
    }    
}
