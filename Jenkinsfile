pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Check nodeJs') {
      steps {
        sh 'node --version'
      }
    }
     stage('Check hostname') {
          steps {
            sh 'cat /etc/hostname'
          }
        }
  }
}
