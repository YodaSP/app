pipeline {
    agent any
tools {
        // Install the Maven version configured as "M3" and add it to the path.
               maven "maven3.8.4"
           }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        
        
        
        stage('build') {
            steps {
                
                    sh 'mvn clean install'
            
        }
        }
        
        stage('Deploy'){
            steps{
                
            
        }
        
    }
}
}
