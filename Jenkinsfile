pipeline{
    agent any
    stages{
        stage("testing-stage"){
            steps{
                sh '''
                       echo "Hello world"
                       sudo apt update
                       sudo mkdir /home/ubuntu/test
                       sudo su
                       cd /home/ubuntu/test
                       touch test.txt
                       echo "Hello world" > test.txt
                       cat test.txt
                       ------ It works--------------
                   '''
            }
        }
    }
    
}
