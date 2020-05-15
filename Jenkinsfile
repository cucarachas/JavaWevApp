pipeline{
	
	agent any
	
	stages{
		stage("Git checkout"){
			steps{
				git "https://github.com/cucarachas/JavaWevApp.git"
			}
		}
		stage("Package"){
			steps{
				sh "mvn clean package"
			}
		}
	    
	}

}