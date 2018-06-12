pipeline {
  agent any
  tools{
 	maven 'Maven 3.3.9'
        jdk 'jdk8'
      }
  stages{
     stage('Display Java home and Maven Home'){
	steps{
	  echo $JAVA_HOME
	  echo MAVEN_HOME
	  echo "Hello World"
	  }
       }
   }
}
