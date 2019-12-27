pipeline {
  agent {
    docker {
      image 'go'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'export GOPATH=`pwd`'
        sh 'echo $GOPATH'
      }
    }

  }
}