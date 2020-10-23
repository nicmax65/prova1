
  
  
// Script //
node{
  stage('SCM Checkout'){
    echo 'SCM Checkout....'
    git branch: 'main', changelog: false, poll: false, url: 'https://github.com/nicmax65/prova1.git'
  }
  
  stage('Compile-Package'){
    echo 'Compile-Package....'
    sh 'mvn package'
  }
}
