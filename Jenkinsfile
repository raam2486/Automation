pipeline {
  agent any
  stages {
    stage('Build_Stage') {
      steps {
        build(job: 'Build_Automation', propagate: true)
      }
    }

  }
}
