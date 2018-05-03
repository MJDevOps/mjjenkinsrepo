pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('Greetings') {
      steps {
        echo 'Hello MJ!!!'
        sh 'java -version'
        echo 'Hello ${MyName}!'
      }
    }
  }
  environment {
    MyName = 'Madhavi'
  }
}