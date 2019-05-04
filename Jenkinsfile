  node
  {
  
   stage('Checkout external proj') 
   {
        
            git branch: 'master',
                credentialsId: 'anurag4516',
                url: 'git@github.com:kuberguy/helloworld.git'

            sh "ls -lat"
        

    }
    stage("Compile & Build Sources from Maven")
    {

    }
    stage("Build Docker Image for generated jar")
    {

    }
    stage("Push Docker Image to registory")
    {

    }
  }