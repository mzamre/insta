pipeline {
	agent any 
	
	stages {
	    stage('Checkout') {
	        steps {
		       url: "https://github.com/mzamre/insta.git"
		      }}
		stage('Build') {
	           steps {
			  sh 'ansible --version'
	                 }}
		
}}

