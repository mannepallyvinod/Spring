#!groovy
pipeline {
	agent none
  stages {
  	stage('Maven Install') {
    	agent {
      	any   {
               image 'maven:3.8.6'
        }
      }
      steps {
      	bat 'mvn clean install'
      }
    }
  }
}
