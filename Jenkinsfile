pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000 npm install'
    }

  }
  stages {
    stage('') {
      steps {
        sh 'echo "running"'
      }
    }
  }
}