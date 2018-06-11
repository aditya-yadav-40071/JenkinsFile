pipeline{
  agent any
  stages{
     stage('My first script'){
	steps{
          pwd
	  echo "Hello World"
	  }
       }
    }
 }

