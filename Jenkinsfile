pipeline {
  agent any

  stages{
    
    stage('Introduction'){
      steps{
        echo 'Welcome this is introduction step'
        script{
          sleep(2)
        }
      }
    }
    stage('Execution'){
      steps{
        echo ' this is execution step'
        script{
          sleep(7)
        }
      }
    }

    stage('Conclusion'){
      steps{
        echo 'this is conclusion step'
        script{
          sleep(4)
        }
        echo ' after 4 sec sleep'
      }
    }
  }
}
