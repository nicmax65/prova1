
  
  
// Script //
node{
  stage('SCM Checkout'){
    echo 'SCM Checkout....'
    git branch: 'main', changelog: false, poll: false, url: 'https://github.com/nicmax65/prova1.git'
      //git 'https://github.com/nicmax65/prova1/'
  }
  
  stage('Compile-Package'){
    echo 'Compile-Package....'
    sh 'mvn package'
  }
}
