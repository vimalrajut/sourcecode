pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello'
      }
    }
    stage('deploy') {
      steps {
        build 'githook/master'
      }
    }
  }
}
