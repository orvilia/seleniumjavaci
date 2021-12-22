node {
	stage ('SCM checkout'){
		git "https://github.com/orvilia/seleniumjavaci"
		}
	stage ('Build'){
    	dir("seleniumjavaci") {
	   bat "mvn clean install"
       }
       	dir("seleniumjavaci/target") {
	   bat "java -jar com.test-1.0-SNAPSHOT.jar"
       }
		}
}
