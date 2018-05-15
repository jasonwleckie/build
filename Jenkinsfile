pipeline {
	agent none
	environment {
		NODE_VER = '8.1.0'
	}	
	stages {
		stage('Beginning') {agent any
		    environment {
		      NEW_VER = 'jason ver'
		    }
			 steps {
				 echo 'Hello world'
				 sh 'echo $NODE_VER'
				 echo "${env.NEW_VAR}"
			}
		}
		stage ('Who am I?') {agent any
			steps {
				echo "${env.NEW_VAR}"
				sh 'curl ipecho.net/plain'
		 	      }
			
		}
	}
}
