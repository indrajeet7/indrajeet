pipeline {
  agent {
    docker {
      image 'python'
    }

  }
  stages {
    stage('run') {
      steps {
        sh ' 	sh python multiing.py'
      }
    }
  }
}