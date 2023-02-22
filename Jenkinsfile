
pipeline {
    agent any
    tools{
        nodejs "NJS"
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
