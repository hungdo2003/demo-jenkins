pipeline {
    agent any 
    stages {
         stage('Clone') { 
            steps {
               git 'https://github.com/hungdo2003/demo-jenkins.git'
            }
        }
        stage('Build') { 
            steps {
               echo"Building..."
            }
        }
        stage('Test') { 
            steps {
                echo"Testing..."
            }
        }
        stage('Deploy') { 
            steps {
                echo"Deploying.."
            }
        }
    }
}