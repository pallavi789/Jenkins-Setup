pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'My first commit'
        sh './mvnw clean compile'
      }
    }

    stage('Unit Testing') {
      steps {
        sh './mvnw test'
      }
    }

  }
}