pipeline {
  agent any
  stages {
    stage('Hello World') {
      steps {
        echo 'Hola Mundo'
      }
    }

    stage('Compile') {
      steps {
        sh 'mvn clean isntall'
      }
    }

    stage('Ended') {
      steps {
        echo 'Terminado'
      }
    }

  }
}