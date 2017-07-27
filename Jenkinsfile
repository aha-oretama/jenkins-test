stage('wait') {
  lock('test') {
    node {
      echo 'start'
    }
  }
}

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
          sh 'sleep 300'
        }
      }
    }
  }
}
