pipeline {
    agent any
    stages{
        
        stage ('Deploy') {
            steps{
                sshagent(credentials : ['90c9c28e-0c41-4a44-9fb7-0571a0decc72']) {
                    sh 'ssh -o StrictHostKeyChecking=no ec2-user@172.31.36.117 touch file2'
                }
            }
        }
        
         
        
    }
}
