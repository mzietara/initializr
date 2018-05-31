pipeline {
  agent {
    docker {
      image 'openjdk:8-alpine'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'sh \'./mvnw -X clean install -Pfull\''
      }
    }
  }
}