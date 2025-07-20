pipeline {
    agent any
    
    tools {
        maven 'maven3.9'
        jdk 'jdk17'
    }

    stages {
        stage('GIT Checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/mjguru1996/boardgame_java.git'
            }
        }
        
        //stage('Compile') {
          //  steps {
            // sh 'mvn compile'
            //}
        //}
        
        //stage('Test') {
          //  steps {
            //  sh 'mvn test' 
            //}
        //}
        
        //stage('Build') {
            //steps {
            //  sh "mvn package"
          //  }
        //}
    }
}
