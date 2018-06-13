pipeline {
  agent {
    docker {
      image 'node:latest'
      args '-p 3100:3100'
    }

  }
  stages {
    stage('buid') {
      steps {
        echo 'hola'
        sh 'sh \'npm install\''
      }
    }
  }
}