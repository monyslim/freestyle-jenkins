pipeline{
    agent any
    stages{
        stage("testing-stage"){
            steps{
                sh '''
                       echo "Hello world"
                       sudo apt-get update 
                       sudo apt-get upgrade -y
                       sudo mkdir /home/ubuntu/test
                       cd /home/ubuntu/test
                       sudo touch test.txt
                       sudo echo "Hello world" > test.txt
                       cat test.txt
                   '''
            }
        }
    }
    
}
