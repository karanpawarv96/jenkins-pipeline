pipeline {
agent any

	stages {
		stage ('install-nginx')
		{
			steps {
				sh 'sudo apt update -y'
				sh 'sudo apt install nginx -y'
			      }
       }
     }
   }
