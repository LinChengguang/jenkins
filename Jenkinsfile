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

    stage('test') {
      steps {
        sh 'mvn test'
      }
    }

  }
}