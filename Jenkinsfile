pipeline {
	agent any
	tools {
		maven 'MVN_HOME'
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
		stage('Build') {
			steps {
				git branch: 'master'
				url: 'https://github.com/trayii/greenhousepro.git'
				}
			}
		}
	}