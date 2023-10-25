pipeline{
agent any 
  environment{
    NEW='1.3.0'
  }
stages {

  stage("build"){
    steps{
      
      echo "Iam build @ ${NEW}"
      withCredentials([usernamePassword(credentials:'79a546f6-c7a0-4baa-92d1-c6faa562d72c',usernameVariable:user,passwordVariable:pwd)]){

        echo "${user}"
      }
      
    }
  }
  stage("deploy"){
    steps{
      echo "Iam Deploying "
    
    }
  }
}
  

  
}
