stage('wait') {
  lock('test') {
    node {
      disableConcurrentBuilds {
        timestamps{
          sh 'sleep 300'
          sh 'sleep 300'
        }
      }
    }
  }
}
