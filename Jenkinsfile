pipeline {
  agent any
  options {
    disableConcurrentBuilds()
  }
  lock('test') {
  }
  stages {
    stage('echo') {
      steps {
        sh 'sleep 300'          
      }
    }
  }
}
