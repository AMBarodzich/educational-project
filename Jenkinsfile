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
				'''
				    rm -rf second
				    mkdir second
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
