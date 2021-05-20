pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}

		stage('Test') {
			steps {
				echo "Test"
			}
		}

		stage('Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
	}	
	
	post {
			always{
				echo "I Run always "
			}
			success{ 
				echo "I Run when you are a success"
			}
			failure{
				echo "I run when you fail"
			}
		}	
}
