pipeline {
  agent any
  tools{
 	maven 'LocalMaven'
        jdk 'LocalJDK8'
      }
  stages{
     stage('Display Java home and Maven Home'){
	steps{
	   sh 'echo ${JAVA_HOME}'
	   sh 'echo ${MAVEN_HOME}'
	   echo "Hello World"
	  }
       }
   }
}
