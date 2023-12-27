pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Clone the Git repository
                git 'https://github.com/red0074/jenkinpipelinejava.git'
            }
        }
        
        stage('Build') {
            steps {
                // Build your Java code
                sh 'javac Nothing.java'
            }
        }
        
        stage('Run') {
            steps {
                // Run your Java code
                sh 'java Nothing'
            }
        }
    }
}
