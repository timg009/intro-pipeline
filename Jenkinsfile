pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Say hello') {
      steps {
        echo "hello ${MY_NAME}"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}