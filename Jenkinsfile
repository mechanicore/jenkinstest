pipeline {
  agent any
  stages {
    stage('Install dependencies') {
      parallel {
        stage('Install dependencies') {
          steps {
            sh 'npm install'
          }
        }
        stage('Bulid') {
          steps {
            sh 'npm run lint'
          }
        }
      }
    }
  }
}