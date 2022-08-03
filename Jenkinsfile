pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Tests') {
			steps {
				echo "Tests"
			}
		}
		stage('Integration Tests') {
			steps {
				echo "Integration Tests"
			}
		}
	} post {
		always {
			echo 'I'm awesome. I run always'
		}
		success {
			echo 'I run on success'
		}
		success {
			echo 'I run on failed'
		}
	}
	}	
		
	}
	
}
