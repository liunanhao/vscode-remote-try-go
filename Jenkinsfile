pipeline {
  agent {
    docker {
      image 'go'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'go get -u https://github.com/liunanhao/vscode-remote-try-go'
        sh 'go build .'
      }
    }

  }
}