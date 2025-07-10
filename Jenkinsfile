pipeline {
  agent any
  stages {
    stage('parallel tests') {
      parallel {
        stage('unit tests') {
          steps {
            sh 'echo "running unit tests..."'
          }
        }

        stage('integration tests') {
          steps {
            sh 'echo "running integration tests..."'
          }
        }

        stage('code lint') {
          steps {
            sh 'echo "liniting code.."'
          }
        }

      }
    }

  }
}