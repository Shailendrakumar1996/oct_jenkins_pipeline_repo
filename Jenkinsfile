pipeline{
    agent any
    stages{
        stage("stage1"){
            steps{
                sh 'sleep 5'
                echo "this is stage1"
            }
        }
        stage("stage2"){
            steps{
                sh '''
                #!/bin/bash
                pwd
                ls -lrt
                sleep 5
                '''
                echo "this is stage2"
            }


        }


        stage("stage3"){
            steps{
                sh '''
                #!/bin/bash
                pwd
                ls -lrt
                sleep 5
                '''
                echo "this is stage3"
            }


        }
        stage("stage4"){
            steps{
                sh '''
                #!/bin/bash
                pwd
                ls -lrt
                sleep 5
                '''
                echo "this is stage4"
            }


        }

         

    } 







}