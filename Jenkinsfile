pipeline {
    agent any
    
    tools {
        jdk "jdk 1.8.0_112"
        
        maven "maven-3.3.3"
    }
    stages {
        stage('Build') { 
            steps { 
                echo 'make' 
            }
        }
        stage('Test'){
            steps {
                echo 'yes we test'
//                sh 'make check'
//                junit 'reports/**/*.xml' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'pirates'
//                sh 'make publish'
            }
        }
    }
    
}