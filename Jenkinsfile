pipeline{
	agent any
	tools{
		nodejs '7.8.0'
	}
	stages {
		stage('Test') {
			steps{
				sh 'npm version'
			}
		}
	}
}
