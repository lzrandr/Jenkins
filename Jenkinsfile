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
	}

    post {
		always {
			echo 'Im awesome. I run always'
		}
		success {
			echo 'I run on success'
		}
		failure {
			echo 'I run on failed'
		}
	}
}
