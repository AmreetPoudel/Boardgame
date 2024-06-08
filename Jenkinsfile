pipeline {
    agent {
        label "agent1"
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
        
        stage('test') {
            steps {
                sh 'mvn test'
            }
        }
        
        
       

             
    }
}
