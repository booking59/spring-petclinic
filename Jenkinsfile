pipeline {
  agent {
    node {
      label 'linux'
    }
    
  }
  stages {
    stage('Checkout') {
      steps {
        sh 'checkout scm'
      }
    }
  }
}