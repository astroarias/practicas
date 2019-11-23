pipeline {
  agent any
  stages {
    stage('Instanciar') {
      steps {
        echo 'Iniciando Proceso'
        bat 'systeminfo'
      }
    }

    stage('Build') {
      steps {
        bat 'gcc --version'
      }
    }

  }
}