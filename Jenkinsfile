stage('wait') {
  lock('test') {
    node {
      options {
        disableConcurrentBuilds()
      }
      sh 'sleep 300'
      sh 'sleep 300'
    }
  }
}
