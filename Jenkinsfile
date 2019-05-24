pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                error (
                    this "errorerd"
                      )
                
                echo 'Deploying....'
            }
        }
    }
    post {
        success { 
            echo "Hello World"
        }
        failure {
            echo "I failed :("
        }
    }
    }
    

