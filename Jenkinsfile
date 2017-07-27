stage('wait') {
  lock('test') {
    node {
      options {
        disableConcurrentBuilds()
        timestamps()
      }
      sh 'sleep 300'
      sh 'sleep 300'
    }
  }
}
