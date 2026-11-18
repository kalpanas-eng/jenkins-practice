
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello Jenkins'

                bat 'echo Compiling Application'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Application'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Application'
            }
        }
    }
}
