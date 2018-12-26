pipeline {
  agent {
    docker {
      image 'python'
      args 'python ping.py'
    }

  }
  stages {
    stage('run') {
      steps {
        sh 'python multiping.py'
      }
    }
  }
}