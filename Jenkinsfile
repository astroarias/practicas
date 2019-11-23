pipeline {
  agent any
  stages {
    stage('Instanciar') {
      steps {
        echo 'Iniciando Proceso'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'uname -a'
          }
        }

        stage('Build Web') {
          steps {
            sh 'php --version'
          }
        }

      }
    }

  }
}