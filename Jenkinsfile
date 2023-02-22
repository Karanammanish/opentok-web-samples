
pipeline {
    agent any
    tools{
        nodejs "NJS"
    }
    stages {
        stage('NPM-Dependency') { 
            steps {
                sh 'ldd --version'
                sh 'npm install 16' 
            }
        }
        stage('Build'){
            steps{
                sh 'npm config ls'
            }
        }
    }
}
