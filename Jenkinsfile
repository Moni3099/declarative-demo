pipeline{
	    agent any
	    stages{
	        stage('Git Checkout'){
	            steps{
	                git credentialsId: 'github', url: 'https://github.com/Moni3099/declarative-demo'
	                
	            }
	        }
	        stage('Mvn sh cmd'){
	           steps{
	              sh label: '', script: 'mvn  clean  package'
	                  }
	               }
	           }
	      }
