pipeline {
    agent any

    stages {             
        stage('Stage-1 , npm install') {
            steps {
                sh 'npm install'
            }
        } 
        stage('Stage-2 , Deploy') {
            steps {
               sh 'echo "deploying application..."'
            }               
        }
    }
}
