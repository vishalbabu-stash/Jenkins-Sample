pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is build stage'
      }
    }

    stage('Test') {
      steps {
        echo 'This is test'
      }
    }

    stage('Approval') {
      steps {
        input 'do you wat to proceed'
      }
    }

    stage('Deploy') {
      steps {
        echo 'deploy complete'
      }
    }

  }
}