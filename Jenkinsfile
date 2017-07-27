stage('wait') {
  disableConcurrentBuilds()
  timestamps()
  lock('test') {
    node {
      sh 'sleep 300'
      sh 'sleep 300'
    }
  }
}
