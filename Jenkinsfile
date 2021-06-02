node{
  stage('SCM Checkout'){
     git 'https://github.com/mgupta87/Demo.git'
   }
  stage('building war file from maven'){
    
   def mvnHome =  tool name: 'maven-3', type: 'maven'   
      bat "${mvnHome}/bin/mvn package" 
  }
}
