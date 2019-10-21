node('master'){
	   stage('git checkout'){
	                  git 'https://github.com/jyotheesh/Inglibraryui.git'
	              }
	   stage('angular build'){
               '''
	             sh 'npm install'
	             sh 'ng build'
               '''
     }
  stage(' deplot to tomcat '){
        deploy adapters: [tomcat9(credentialsId: '54006a95-aa56-43ba-8c55-32b6f7c330eb', path: '', url: 'http://13.235.238.59:8090')],
          contextPath: 'sample', war: '**/*.war'
  }
	
	
	}
