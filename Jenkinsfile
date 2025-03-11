pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    sh 'g++ -o PES2UG22CS608-1 main.cpp' 
                }
            }
        }

        stage('Test') {
            steps {
                script {
                    sh './PES2UG22CS608-1' 
                }
            }
        }

        stage('Deploy') {
            steps {
                script {
                    echo 'Deploying the application...'
                    .
                }
            }
        }
    }

    post {
        failure {
            echo 'Pipeline failed'
        }
    }
}
