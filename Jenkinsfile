pipeline {
  agent any

  stages{
    stage("Build"){
      steps{
        echo 'Building step from Git'
      }
    }
    stage("Test"){
      steps{
        echo 'Testing step from Git'
      }
    }
    stage("Package"){
      steps{
        echo 'Packaging step from Git'
      }  
    }  
  }

  post{
    always{
      echo 'This pipeline is completed.'
    }
  }
}
