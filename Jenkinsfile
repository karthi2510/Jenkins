pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'df -h'
      }
    }

    stage('java testing') {
      steps {
        sh 'java java1.java'
      }
    }

  }
}