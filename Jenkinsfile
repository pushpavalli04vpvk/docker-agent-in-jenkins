pipeline {
	agent { Dockerfile true	}
	stages {
		stage('Build'){
			steps {
				sh '''
				   git --version
				   curl --version
				'''
			}
		}
	}
}
