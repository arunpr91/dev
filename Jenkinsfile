pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Checkout the code from your Git repository
                git 'https://github.com/Rsowmya26/dev.git'
                
                // Build the Maven project
                bat 'mvn clean package'
            }
        }
        
        stage('Build') {
            steps {
                // Run Maven tests
                bat 'mvn build'
            }
        }
    }
}
