pipeline{
agent any 
  environment{
    NEW='1.3.0'
    Githubcred=credentials('79a546f6-c7a0-4baa-92d1-c6faa562d72c');
  }
stages {

  stage("build"){
    steps{
      
      echo "Iam build @ ${NEW}"
      
    }
  }
  stage("deploy"){
    steps{
      echo "Iam Deploying ${Githubcred}"
      sh "${Githubcred}"
    }
  }
}
  

  
}
