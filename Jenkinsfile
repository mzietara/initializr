pipeline {
  agent {
    docker {
      image 'openjdk:8-alpine'
    }

  }
  stages {
    stage('error') {
      steps {
        sh './mvnw -X clean install -Pfull'
      }
    }
  }
}