
pipeline {
    agent any
    tools{
        nodejs "NJS"
    }
    stages {
        stage('NPM-Dependency') { 
            steps {
                sh 'ldd --version'
                sh 'nvm install 16'
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
