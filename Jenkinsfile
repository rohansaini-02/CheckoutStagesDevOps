pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'main' , url : 'https://github.com/rohansaini-02/PractiseDebOps' 
                echo 'Git Checkout'
            }
        }
        stage('Build'){
            steps{
                echo 'Build Stage'
            }
        }
        
         stage('Test') {
            steps {
                echo 'Test Stage'
            }
        }

         stage('Deploy') {
            steps {
                echo 'Deploy Stage'
            }
        }
    }
}