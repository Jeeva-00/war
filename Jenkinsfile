pipeline {
  agent any
  stages {
    stage('manual q/a approval') {
      steps {
        input 'approve to deploy to prod?'
      }
    }

    stage('prod-deploy') {
      steps {
        echo 'deploying to prod...'
      }
    }

  }
}