pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'message'
            echo 'fist step'
          }
        }

        stage('parralel') {
          steps {
            echo 'second step'
          }
        }

      }
    }

    stage('build') {
      steps {
        echo 'third step'
      }
    }

    stage('clean up') {
      steps {
        echo 'forth step'
      }
    }

  }
}