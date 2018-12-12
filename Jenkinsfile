pipeline {
    agent any 
	stages {
	    stage('Example Build') {
		   
		     steps {
			    
				 echo 'Hello, I am going to start'
				 
				 }
		}
		stage('Example Build1') {
		   
		     steps {
			    
				 echo 'Hello, I am testing'
				 
				 }
		}
		stage('Docker Build') {
		   
		     steps {
			    
				 sh """ docker build -t sainadh463/testapp . """
				 
				 }
		}
    }
    }
