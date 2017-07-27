pipeline {
  agent any
  options {
    disableConcurrentBuilds()
  }
  stages {
    stage('echo') {
      steps {
        lock('test') {
        sh 'sleep 300'
        }
      }
    }
  }
}
