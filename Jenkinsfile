pipeline{
agent any 
  environment{
    NEW='1.3.0'
  }
  parameters{
    choice(name:'Version',choices:['1.1','1.2','1.3'],descprition:'Iam Choices description')
      booleanParam(name:'exec',defaultValue:true,description:'Helobooleandesc')
  }
        
stages {

  stage("build"){
    steps{
      
      echo "Iam build @ ${NEW}"
      echo "choices are ${params.Version}"
      
    }
  }
  stage("deploy"){
    steps{
      echo "Iam Deploying "
    
    }
  }
}
  

  
}
