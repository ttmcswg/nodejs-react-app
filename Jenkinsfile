pipeline {
  agent {
    docker {
      image 'node:8-jessie'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('test') {
      steps {
        sh '''docker ps
npm install'''
      }
    }
  }
}