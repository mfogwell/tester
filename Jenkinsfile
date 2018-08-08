pipeline {
  agent any
  stages {
    stage('Build2') {
      steps {
        echo 'Hello JAM'
        sleep 5
      }
    }
    stage('') {
      steps {
        sh './jenkins/build.sh'
      }
    }
  }
}