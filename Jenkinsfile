pipeline{
    agent any
    environment{
        PATH = "/opt/apache-maven-3.6.3/bin:$PATH"
    }
    stages{
        stage("Git checkout from SCM jenkisfile"){
            steps{
                git 'https://github.com/krishna1857/classdemo'
            }
        }
        stage("Maven Build"){
            steps{
                sh "mvn clean package"
            }
        }
    }
}
