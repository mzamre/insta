pipeline {
	agent any 
	
	stages {
	    stage('Checkout') {
	        steps {
		       sh '''
	                 cd /home/mohit
			 touch mohitfile12
                       '''
		      }}
		stage('Build') {
	           steps {
			  sh 'ansible --version'
	                 }}
		
}}

