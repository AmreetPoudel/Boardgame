pipeline {
    agent {
        label "node1"
    }
    tools{
        maven "maven-3"
    }

    stages {

        
        stage('compile') {
            steps {
                sh 'mvn compile'
            }
        }
        
        stage('testing') {
            steps {
                sh 'mvn test'
            }
        }
        
        
       

             
    }
}
