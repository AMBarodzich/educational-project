pipeline {
	agent any 		
	
	stages {
		stage("build"){
			steps {
				echo 'first stage'
				sh 'uptime'
			}
		}
		stage("test"){
			steps {
				echo 'second stage'
				sh '''
				    rm -rf second
				    mkdir second
				    java --version
				    java --version
				    java --version
				    java --version
				    java --version
				    java --version
				    java --version
				    java --version
				'''    
			}
		}
		stage("deploy"){
			steps {
				echo 'third stage'
				sh 'java --version'
			}
		}
	}
}
