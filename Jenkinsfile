pipeline 
{
    agent any
    stages 
    {
        stage('Install Docker') 
        {
            steps 
            {
                sh "yum install docker -y"
                sh "service docker start"
                sh "service docker status"
                echo "Docker Installed"
            }
        }
    }
}
