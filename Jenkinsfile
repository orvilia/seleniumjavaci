node {
	stage ('SCM checkout'){
		git "https://github.com/orvilia/seleniumjavaci"
		}
	stage ('Build'){
       {
	   bat "mvn clean install"
       }
       	dir("target") {
	   bat "java -jar com.test-1.0-SNAPSHOT.jar"
       }
		}
}
