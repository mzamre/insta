pipeline {
	agent any 
	
	stages {
	    stage('Checkout') {
	        steps {
			checkout scm			       
		      }}
		stage('Build') {
	           steps {
			  sh '/home/mohit/Downloads/apache-maven-3.9.6-bin/apache-maven-3.9.6/bin/mvn install'
	                 }}
		stage('Deployment'){
		   steps {
		sh 'cp target/insta.war /home/mohit/Downloads/apache-tomcat-9.0.89/webapps'
			}}	
		stage('Docker build'){
		    steps {
			sh 'docker build -t mohitzamre/pipelineimage1 .'
			}}
			
}}
