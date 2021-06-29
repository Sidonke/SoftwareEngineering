pipeline {
    
  agent any
    
    
    stages {
       
        stage("run backend") {
            steps{
                echo 'executing gradle...'
                withGradle() {
                    sh './gradlew -v'
                }
            }
        }
        
        stage("build") {
            steps {
                echo 'building the application'
                
            }
        }
        stage("test") {
            steps {
                echo 'testin the application'
            }
        }
        stage("deploy") {
            steps {
                echo 'building the application'
            }
        }
    }   
}
