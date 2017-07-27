lock('test') {
pipeline {
  agent any
  options {
    disableConcurrentBuilds()
  }
  stages {
    stage('echo') {
      steps {
        sh 'sleep 300'
        sh 'sleep 300'
      }
    }
  }
}
}
