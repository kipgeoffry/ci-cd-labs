pipeline {
  agent {
    docker { image 'kipgeoffry/jenkins-agent-node:20.5.1' }
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
