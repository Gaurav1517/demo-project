pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                // Clone the repository from GitHub
                git branch: 'main', url: 'https://github.com/Gaurav1517/java-maven-webapp.git'
            }
        }
        
        stage('Print Message') {
            steps {
                // Print 'hello' to console output
                sh 'echo hello'
            }
        }
    }
}
