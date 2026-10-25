pipeline{
    agent any
    stages{
        stage  ("stage1") {
          steps{
            sh 'sleep 5'
             echo "this is stage1"
          }
        }
         stage  ("stage2") {
            steps{
                sh '''
               #!/bin/bash
               ls -lrt
               pwd
               sleep 5

                '''
              echo "this is stage2"
          }
        }
        
    }
}