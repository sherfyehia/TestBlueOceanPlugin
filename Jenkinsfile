pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build done'
      }
    }

    stage('test1') {
      steps {
        echo 'test done'
      }
    }

    stage('deploy') {
      steps {
        echo 'done deploy'
        input(message: 'Are you sure want to deploy ?', ok: 'yes iam sure')
      }
    }

    stage('done depoly successfull') {
      steps {
        echo 'done depoly successfull'
      }
    }

  }
}