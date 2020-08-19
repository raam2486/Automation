pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'Build_Automation', propagate: true)
      }
    }

  }
}