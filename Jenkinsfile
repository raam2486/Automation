pipeline {
  agent any
  stages {
    stage('BuildStage') {
      steps {
        build(job: 'Build_Automation', propagate: true)
      }
    }

  }
}
