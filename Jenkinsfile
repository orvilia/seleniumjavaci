node {
	stage ('Code Checkin'){
		git "https://github.com/orvilia/seleniumjavaci"
		}
	stage ('Automation Build'){
       
	   bat "mvn clean install"
       }
}
