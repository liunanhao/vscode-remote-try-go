pipeline {
  agent {
    docker {
      image 'go'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'go build .'
      }
    }

  }
}