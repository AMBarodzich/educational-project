pipeline {
	agent any 

	stages {
		stage("build") {
			steps {
				echo 'first stage'
				sh 'uptime'
			}
		}
		stage("test") {
			steps {
				echo 'second stage'
				sh 'mkdir test'
			}
		}
		stage("deploy") {
			steps {
				echo 'third stage'
				sh 'java --version'
			}
		}
	}
}
