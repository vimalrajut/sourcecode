pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello - World!'
	sh "mvn install"
      }
    }
    stage('deploy') {
      steps {
   	echo 'build success'
      }
    }
  }
}
