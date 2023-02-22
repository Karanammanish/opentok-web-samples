
pipeline {
    agent any
    tools{
        nodejs "NJS"
    }
    stages {
        stage('NPM-Dependency') { 
            steps {
                sh 'ldd --version'
                sh 'cd /var/lib/jenkins/workspace/test1/package.json'
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
