pipeline{
    agent any
    stages{
        stage("testing-stage"){
            steps{
                sh '''
                       echo "hello world"
                       pwd
                       sudo mkdir /home/ubuntu/test
                       echo "Welcome" > /home/ubuntu/test/test.txt
                   '''
            }
        }
    }
    
}
