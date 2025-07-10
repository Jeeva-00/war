pipeline {
  agent any
  stages {
    stage('Archive logs') {
      steps {
        sh '''echo "Run on: $(date)" > build-info.log
'''
        archiveArtifacts 'build-info.log'
      }
    }

  }
}