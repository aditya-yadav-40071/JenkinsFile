pipeline {
  agent any
  tools{
 	maven 'LocalMaven'
        jdk 'LocalJDK8'
      }
  stages{
     stage('Display Java home and Maven Home'){
	steps{
          sh '''
	   echo ${JAVA_HOME}
	   echo ${MAVEN_HOME}
	   echo "Hello World"
          '''
	  }
       }
   }
}
