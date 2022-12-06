#!groovy
pipeline {
	agent none
  stages {
  	stage('Maven Install') {
    	agent {
      	maven   {
               image 'maven:3.8.6'
        }
      }
      steps {
      	sh 'mvn clean install'
      }
    }
  }
}
