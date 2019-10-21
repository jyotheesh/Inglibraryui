node('master'){
	   stage('git checkout'){
	                  git 'https://github.com/jyotheesh/Inglibraryui.git'
	              }
	   stage('angular build'){
	             sh 'npm install'
	             sh 'ng build --base-href=/book-management/'
	         }
	
	
	}
