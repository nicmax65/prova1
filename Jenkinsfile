
  
  
// Script //
node{
  stage('SCM Checkout'){
    echo 'SCM Checkout....'
      git 'https://github.com/nicmax65/prova1/'
  }
  
  stage('Compile-Package'){
    echo 'Compile-Package....'
    sh 'mvn package'
  }
}
