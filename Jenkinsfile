pipeline {
  agent {
    docker {
      image 'go'
    }

  }
  stages {
    stage('build') {
      steps {
        sh '''export GOPATH=`pwd`
cd src/main
go build .'''
        sh 'ls src/main'
      }
    }

  }
}