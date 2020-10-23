// Declarative //
pipeline {
    agent any
    
    stages {
      stage('SCM Checkout'){
        git 'https://github.com/nicmax65/prova1/'
      }

      stage('Compile-Package'){
        sh 'mvn package'
      }
    }
}
  
  
// Script //
//node{
//  stage('SCM Checkout'){
//    git 'https://github.com/nicmax65/prova1/'
//  }
  
//  stage('Compile-Package'){
//    sh 'mvn package'
//  }
//}
