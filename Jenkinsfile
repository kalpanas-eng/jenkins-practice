pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello Jenkins'
        bat 'ho "Compiling Application"'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing successful'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployment successful'
      }
    }

  }
}