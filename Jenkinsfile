pipeline{
    agent any
    stages{
        stage("testing-stage"){
            steps{
                sh '''
                       echo "Hello world"
                       sudo apt update
                       sudo mkdir /home/ubuntu/test
                       cd /home/ubuntu/test
                       sudo touch test.txt
                       sudo echo "Hello world" > test.txt
                       cat test.txt
                       ------ It works--------------
                   '''
            }
        }
    }
    
}
