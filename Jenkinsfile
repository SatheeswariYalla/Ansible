pipeline {
  agent {
    node {
      label 'Test Node'
    }

  }
  stages {
    stage('Dev 1') {
      steps {
        retry(count: 5) {
          sh 'echo "hello Dev"'
        }

      }
    }
    stage('Test') {
      steps {
        sh 'echo "Hello Test"'
      }
    }
  }
}