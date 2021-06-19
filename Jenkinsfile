pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'This is a build step'
      }
    }

    stage('test') {
      steps {
        sh 'mvn test'
      }
    }

  }
}