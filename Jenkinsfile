pipeline {
  agent any
  stages {
    stage('A01') {
      parallel {
        stage('A01') {
          steps {
            sh 'dotnet clean'
          }
        }
        stage('A11') {
          steps {
            sh 'dotnet clean'
          }
        }
        stage('A21') {
          steps {
            sh 'dotnet clean'
          }
        }
      }
    }
    stage('A02') {
      steps {
        sh 'dotnet clean'
      }
    }
    stage('') {
      steps {
        sh 'dotnet clean'
      }
    }
  }
}