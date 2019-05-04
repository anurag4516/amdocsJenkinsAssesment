  node
  {
  
  stage('Checkout external proj') {
       
            // I have configured credentials in Jenkins with its id as anurag4516 & set password
            //We can also do ssh cloning for that we need to add public key to git 
            git branch: 'master',
                credentialsId: 'anurag4516',
                url: 'https://github.com/kuberguy/helloworld.git'

            sh "ls -lat"
            echo "Successfully Checkout of project "
        
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