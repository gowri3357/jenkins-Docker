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
			 sh 'cd /home/ec2-user'   
                         sh 'docker build .'
        }
		}	
    }
}
