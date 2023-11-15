pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Demarrage du stage Test'
        sh 'docker build -t docker-node-example'
        echo 'Fin du stage Test'
      }
    }

  }
}