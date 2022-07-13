pipeline{

agent any

stages{

  stage('CheckOutCode'){
    steps{
    git branch: 'development', url: 'https://github.com/Ajithkolal/mbp_Jenkins.git'
	
	}
  }
  
  stage('Build'){
  steps{
  sh  "mvn clean package"
  }
  }
 }
 
}
