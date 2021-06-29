pipeline {
    
  agent any
    
    
    stages {
       
        
        
        stage("build") {
            steps {
                echo 'building the application'
                sh "gradle install"
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
