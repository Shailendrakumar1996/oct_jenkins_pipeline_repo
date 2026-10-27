pipeline{
        agent any
            environment{
                DOCKER_USER="KUMAR"
                AWS_ACCESS_KEY="12334567789"



            }
                stages{
                        stage(stage1){
                            
                            steps{
                                echo  "DOCKER_USER:$(env.DOCKER_USER)"
                                echo "AWS_ACCESS_KEY:$(env.AWS_ACCESS_KEY)"
                                        sh '''
                                        env
                                        '''     
                            }

                        }
                }















}