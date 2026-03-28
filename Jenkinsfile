pipeline {
  agent any
  stages {
    stage('first ') {
      parallel {
        stage('first ') {
          steps {
            echo 'hello 1'
          }
        }

        stage('second') {
          steps {
            echo 'hello 2'
          }
        }

      }
    }

    stage('third') {
      steps {
        echo 'hello 3'
      }
    }

  }
}