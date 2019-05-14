pipeline {
	agent any
	stages {
		stage ('Clone repository') {
		    steps {
                         checkout scm
        }
		}
		
	stage ('build') {
		    steps {
                         sh 'docker build -t dock .'
        }
		}	
    }
}
