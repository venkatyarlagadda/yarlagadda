pipeline {
  agent {
    docker {
      image 'ode:6-alpine a'
      args '-p 3000:3000 '
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install.'
      }
    }
  }
}