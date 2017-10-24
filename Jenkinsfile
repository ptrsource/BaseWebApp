pipeline {
  agent {
    node {
      label 'mynode'
    }
    
  }
  stages {
    stage('build') {
      steps {
        echo 'hi'
        build(job: 'createVM', propagate: true, quietPeriod: 1, wait: true)
      }
    }
  }
}