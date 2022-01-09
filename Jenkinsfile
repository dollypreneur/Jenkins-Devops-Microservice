pipeline {
	agent any
	//agent {docker {image 'maven:3.8.2'} }
	stages {
		stage ('Build') {
			steps {
			   sh "mvn --version"
		       echo "Build"
			}
		}
		stage ('Test') {
			steps {
			   echo "Test"
			}
		}
		stage ('Integrated Test') {
			steps {
			   echo "Integration Test"
			}
		}
	}	
}			
	