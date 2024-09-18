pipeline {
	agent any 
	
	stages {
	    stage('Checkout') {
	        steps {
		       sh 'cd /home/mohit'
			sh ' touch mohitfile1'
		      }}
		stage('Build') {
	           steps {
			  sh 'ansible --version'
	                 }}
		
}}

