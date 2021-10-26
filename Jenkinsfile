pipeline{
    agent any
    environment{
        PATH = "/opt/apache-maven-3.6.3/bin:$PATH"
    }
    stages{
        stage("Run python file"){
            steps{
                sh 'python hello.py'
            }
        }
    }
}
