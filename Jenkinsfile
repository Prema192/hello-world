pipeline {
    agent any
    environment{
        PATH="/opt/apache-maven-3.8.7/bin:$PATH"
    } 
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    
    stage('Hii') {
            steps {
                echo 'hi prema how are you'
            }
        }
        stage('SCM') {
            steps {
                git 'https://github.com/Prema192/hello-world.git'
            }
        }
    
        stage('Build') {
            steps {
                sh "mvn package"
            }
        }
    }
    
}
