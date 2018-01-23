pipeline {
  agent {
    node {
      label 'linux'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}