
pipeline {
     agent {
        label 'windows'
     }  
    stages {
        stage('version') {
            steps {
				sh 'pwsh --version'
			}
		}
	
    
		stages {
			stage('hello.ps1') {
				steps {
					sh 'pwsh hello.ps1'
				}
			}
		}
	}
}
