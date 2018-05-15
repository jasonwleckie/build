pipeline {
	agent none
	stages {
		stage('Beginning') {agent any
			steps {
				echo 'Hello world'
			}
		}
		stage ('Who am I?') {agent any
			steps {
				sh 'curl ipecho.net/plain'
				
		 	      }
			
		}
	}
}
