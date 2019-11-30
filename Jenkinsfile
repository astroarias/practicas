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
            sleep 1
            echo 'Iniciando el proceso'
          }
        }

        stage('Build Web') {
          steps {
            sh 'date'
            sleep 3
          }
        }

        stage('tiempo de espera') {
          steps {
            echo 'Esperando tiempo'
            sleep 15
          }
        }

      }
    }

  }
}