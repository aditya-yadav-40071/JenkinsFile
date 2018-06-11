pipeline {
  agent any
  stages {
    stage('My first script') {
      steps {
        echo pwd
        sh 'echo step1'
        echo 'Hello World'
      }
    }
    stage('Test') {
      steps {
        sh 'echo "This is test stage"'
      }
    }
  }
}