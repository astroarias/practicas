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
            sh 'chdir'
            sleep 1
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