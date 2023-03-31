pipeline {
  agent any
  stages {
    stage('verify') {
      steps {
        sh 'just --help'
      }
    }
    stage('run') {
      steps {
        sh 'just'
      }
    }
  }
}