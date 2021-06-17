pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
      args '-v /root/.m2:/root/.m2'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'This is a build step'
      }
    }

    stage('Test') {
      steps {
        echo 'This is a test step'
      }
    }

    stage('Deploy') {
      steps {
        echo 'This is a deploy step'
      }
    }

  }
}