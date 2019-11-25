pipeline {
  agent {
    node {
      label 'deploy'
    }

  }
  stages {
    stage('') {
      steps {
        build(job: 'node', quietPeriod: 23)
      }
    }
  }
  environment {
    key = 'dev'
  }
}