pipeline {
  agent {
    node {
      label 'node'
    }

  }
  stages {
    stage('nodejsapp') {
      steps {
        sh 'npm start'
      }
    }
  }
}