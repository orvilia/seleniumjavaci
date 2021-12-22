node {
	stage ('SCM checkout'){
		git "https://github.com/orvilia/seleniumjavaci"
		}
	stage ('Test'){
       
	   bat "mvn clean install"
       }
}
