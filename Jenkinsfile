pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Gaurav1517/java-maven-webapp.git'
            }
        }
        stage('print'){
          steps{
            sh 'echo hello'
          }
        }
   }
}
