pipeline{
    // agent { label 'slave1&&slave2'}
    // agent { label 'slave1||slave2'}
    // agent {!master}
    agent none
    stages{
        stage("stage1"){
            agent {label 'slave1'}
            steps{
                sh 'sleep 5'
                echo "this is stage1"
            }
        }
        stage("stage2"){
            agent {label 'slave2'}
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






    } 







}