
pipeline {
	agent none
	options { skipDefaultCheckout(true) }
	stages {
		stage('Build and Test') {
			agent any
			steps {
				sh 'docker build --tag review-server:0.1'
			}
		}
	}
}
