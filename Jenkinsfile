pipeline{
  agent any
  tools {
  terraform 'terraform'
}
  stages{
    stage('clone the repo'){
      steps{
      git credentialsId: 'git', url: 'https://github.com/mahendra03/jenkins-terraform.git'    
      }
  }
  }
}
  
