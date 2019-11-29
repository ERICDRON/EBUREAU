
pipeline {
    agent any 
    tools {
        maven 'm3'
    }
    stages {
        stage('Build') { 
            steps {
                // 
                  echo 'Etape Build maven'
                    bat 'mvn clean compile'
                    
            }
        }
        
        stage('Test') { 
            steps {
                // 
                echo 'Etape Test'
            }
        }
        
        stage('Packaging') { 
            steps {
                // 
                  echo 'Etape PAckaging'
            }
        }
        
        stage('Deploy') { 
            steps {
                // 
                 echo 'Etape Deploy'
            }
        }
    }
}
