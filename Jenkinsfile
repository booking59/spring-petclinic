pipeline {
  agent {
    node {
      label 'linux'
    }
    
  }
  stages {
    stage('Checkout') {
      steps {
        sh 'sh checkout scm'
      }
    }
  }
}