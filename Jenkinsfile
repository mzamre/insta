pipeline {
	agent any 
	
	stages {
	    stage('Checkout') {
	        steps {
		       sh 'git clone https://github.com/mzamre/insta.git'
		      }}
		stage('Build') {
	           steps {
			  sh 'ansible --version'
	                 }}
		
}}

