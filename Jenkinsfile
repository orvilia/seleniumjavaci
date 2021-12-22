node {
	stage ('SCM checkout'){
		git "https://github.com/orvilia/seleniumjavaci"
		}
	stage ('Build'){
       
	   bat "mvn clean install"
       }
       
       dir("target") {
	   bat "java -jar gitciselenium-0.0.1-SNAPSHOT"
       }
}
