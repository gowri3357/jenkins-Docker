pipeline {
	agent any
	stages {
		stage ('Clone repository') {
		    steps {
            checkout scm
        }
		}
		stage ('Build') {
		    steps {
            			sh 'sudo docker build -t doc-image .'
        }
		}
    }
}
