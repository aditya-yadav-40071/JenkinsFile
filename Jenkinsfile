pipeline {
  agent any
  stages {
    stage('Display Java home and Maven Home') {
      steps {
        sh 'echo ${JAVA_HOME}'
        sh 'echo ${MAVEN_HOME}'
        echo 'Hello World'
      }
    }
    stage('Maven-Version') {
      steps {
        sh 'mvn -version'
      }
    }
  }
  tools {
    maven 'LocalMaven'
    jdk 'LocalJDK8'
  }
}