pipeline{
    agent any
    stages{
        stage("testing-stage"){
            steps{
                sh '''
                       echo "hello world"
                       sudo pwd
                       sudo mkdir /home/ubuntu/test
                       echo "Welcome" > /home/ubuntu/test/test.txt
                   
                   
                   '''
            }
        }
    }
    stages{
        stage("Building the image"){
            steps{
                sh '''
                      echo "it works"
                   '''
            }
        }
    }
}