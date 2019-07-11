pipeline {
  agent {
    node {
      label 'Test Node'
    }

  }
  stages {
    stage('Dev') {
      steps {
        sh 'echo "Hello Dev"'
      }
    }
    stage('Test') {
      steps {
        sh 'echo " Hello Test"'
      }
    }
  }
}