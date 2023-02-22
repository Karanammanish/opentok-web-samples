
pipeline {
    agent any
    tools{
        NodeJs "NJS"
    }
    stages {
        stage('NPM-Dependency') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('Build'){
            steps{
                sh 'npm config ls'
            }
        }
    }
}
