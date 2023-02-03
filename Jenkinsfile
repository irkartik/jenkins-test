pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        sh 'echo "I am a ${BUZZ_NAME}"'
      }
    }

  }
  environment {
    BUZZ_NAME = 'hljkn'
  }
}