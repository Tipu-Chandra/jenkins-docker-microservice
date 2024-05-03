pipeline {
	agent { docker { image 'maven:3.6.3'} }
	stages {
		stage('Build') {
			sh 'mvn --version'
			echo "Build"
		}
		stage('Test') {
			echo "Test"
		}
		stage('Integretaion Test') {
			echo "Integretaion Test"
		}
	}
}
