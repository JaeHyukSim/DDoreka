
pipeline {

	agent none
	options { skipDefaultCheckout(true) }
	stages {
		stage('Build and Test') {
			agent any
			steps {
				sh 'docker build -t review-server:1.0 ./backend/Review
			}
		}
	}
}
