pipeline {
  agent { docker { image 'python:3.11.4-alpine3.18' } }
  // agent any
  stages {
    stage('echo') {
      steps { 
        echo 'Hello Jenkins ...'
      }
    }
    stage('build') {
      steps {
        sh 'python --version'
      }
    }
  }
}
  
