pipeline {
	agent any 
	stages {
		
		stage('build'){
	     steps {
	     	sh 'make'

	     }		
		}

		stage('test'){
			stpes{
				sh 'mke test'
			}
		}	

		stage('deploy'){
			steps{
				sh 'mke publish'
			}
		}




	}



}