pipeline {
  agent any
  stages {
    stage('QA') {
      steps {
        build(job: 'first job', propagate: true, quietPeriod: 2, wait: true)
      }
    }
  }
}