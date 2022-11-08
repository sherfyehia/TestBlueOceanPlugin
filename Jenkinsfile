pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'start build'
      }
    }

    stage('test1') {
      parallel {
        stage('test1') {
          steps {
            echo 'start test 1 '
          }
        }

        stage('test 2') {
          steps {
            echo 'start test 2'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'start deploy'
      }
    }

  }
}