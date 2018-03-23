pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'npm install'
          }
        }
        stage('simultaneous') {
          steps {
            echo 'print this'
          }
        }
      }
    }
  }
}