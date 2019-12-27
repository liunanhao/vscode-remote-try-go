pipeline {
  agent {
    docker {
      image 'go'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'git clone https://github.com/liunanhao/vscode-remote-try-go'
        sh 'cd vscode-remote-try-go && go build .'
      }
    }

  }
}