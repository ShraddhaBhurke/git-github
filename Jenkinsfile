pipeline {
  agent any
  stages {
    stage('clean') {
      steps {
        build 'mvn clean'
      }
    }

  }
  environment {
    clean = 'mvn clean'
  }
}