pipeline {
	agent any
	tools {
		maven 'mvn_home'
	}
	stages {
		stage('Build') {
			steps {
				echo 'hello world'
				sh 'mvn -v'
				}
			}
		stage('QA'){
			steps {
				echo 'Hello JDK' 
				sh 'java -version'
				}
			}
		}
	}
