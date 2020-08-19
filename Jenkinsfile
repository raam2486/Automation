pipeline {
  agent any
  stages {
    stage('') {
      steps {
        git(url: 'https://github.com/raam2486/Automation.git', branch: 'master', poll: true)
        build(job: 'Build_Automation', propagate: true)
      }
    }

  }
}