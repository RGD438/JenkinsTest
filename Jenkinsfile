pipeline {
  agent any
  stages {
    stage('1') {
      parallel {
        stage('1') {
          steps {
            echo 'A'
          }
        }
        stage('2') {
          steps {
            echo 'B'
            echo 'BB'
          }
        }
      }
    }
  }
}