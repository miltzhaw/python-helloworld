pipeline {
  agent any
  stages {
    stage('Build') {
      post {
        failure {
          echo 'Build failed'
        }

      }
      steps {
        echo 'Building...'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing...'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying...'
      }
    }

  }
}