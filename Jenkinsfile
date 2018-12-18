pipeline {
  agent {
    docker {
      image 'python'
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