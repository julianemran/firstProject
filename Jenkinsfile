pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mkdir test'
        sh 'docker build .'
      }
    }

  }
}