
pipeline {
    agent any
    tools{
        nodejs "node"
        // Nodejs and npm should be there in our local machine
    }
    stages {
        stage('BLUID') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
