pipeline{
agent any {
stages {

  stage("build"){
    steps{
      when {
 expression{
  BRANCH_NAME == 'master' 
 }
        
      }
      echo "Iam build "
    }
  }
  stage("deploy"){
    steps{
      echo "Iam Deploying"
    }
  }
}
  
}
  
}
