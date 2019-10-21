node('master'){
	   stage('git checkout'){
	                  git 'https://github.com/mythribhay/Inglibraryui'
	              }
	   stage('angular build'){
	             sh 'npm install'
	             sh 'ng build --base-href=/book-management/'
	         }
	
	
	}
