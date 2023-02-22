
pipeline {
    agent any
    tools{
        NodeJs "NJS"
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
