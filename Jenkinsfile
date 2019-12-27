pipeline {
  agent {
    docker {
      image 'go'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'cd vscode-remote-try-go && go build .'
      }
    }

  }
}