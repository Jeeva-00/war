pipeline {
  agent any
  stages {
    stage('email-notifiy') {
      steps {
        emailext(subject: 'Notification testing', body: 'If you are seeing this msg the pipeline is ececuted successfully ', attachLog: true, to: 'jeevakumaran503@gmail.com')
      }
    }

  }
}