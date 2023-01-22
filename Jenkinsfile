pipeline {
	agent any
	stages {
		stage('Build') {
			steps{
				sh 'docker compose build'
				echo "build created"
			}
		}
		stage('Deploy'){
			steps{
				sh 'docker compose up -d' 
				echo "build deployed"
			}
		}
	}
}
