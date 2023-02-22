
pipeline {
    agent any
    tools{
        NodeJs "NPM"
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
