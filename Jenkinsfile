pipeline {
  agent any
  options {
    disableConcurrentBuilds()
  }
  stages {
    stage('echo') {
      lock('test') {
        steps {
          sh 'sleep 300'          
        }
      }    
    }
  }
}
