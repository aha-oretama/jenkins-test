stage('wait') {
  lock('test') {
  disableConcurrentBuilds {
    timestamps{
        node {
          sh 'sleep 300'
          sh 'sleep 300'
        }
      }
    }
  }
}
