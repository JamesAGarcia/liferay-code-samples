pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        isUnix()
        sh 'ls -la'
        sh './build.sh'
      }
    }
  }
}