pipeline {
  agent {
    node {
      label 'node-test'
    }

  }
  stages {
    stage('install') {
      steps {
        sh 'npm install'
      }
    }

    stage('test') {
      steps {
        sh 'npm test'
      }
    }

  }
}