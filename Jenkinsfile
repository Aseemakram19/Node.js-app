pipeline {
    agent any

    stages {
        stage('Stage-1 , clean ws') {
            steps {
                cleanWs()
            }
        }        
        stage('Stage-2 , npm install') {
            steps {
                sh 'npm install'
            }
        } 
        stage('Stage-3 , Deploy') {
            steps {
               sh 'echo "deploying application..."'
            }               
        }
    }
}
