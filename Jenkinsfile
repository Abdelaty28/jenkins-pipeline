pipeline {
  agent any
  stages {
    stage('first ') {
      parallel {
        stage('first ') {
          steps {
            echo 'hello world 1'
          }
        }

        stage('second') {
          steps {
            echo 'hello world 2'
          }
        }

      }
    }

    stage('third') {
      steps {
        echo 'hello world 3'
      }
    }

  }
}