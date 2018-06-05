pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say hello') {
      steps {
        echo 'hello world'
        sh 'java -version'
      }
    }
  }
}