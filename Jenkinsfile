node {
	stage ('SCM checkout'){
		git "https://github.com/orvilia/seleniumjavaci"
		}
	stage ('Build'){
    	dir("seleniumjavaci") {
	   sh "mvn clean install"
       }
       	dir("comtest/target") {
	   sh "java -jar com.test-1.0-SNAPSHOT.jar"
       }
		}
}
