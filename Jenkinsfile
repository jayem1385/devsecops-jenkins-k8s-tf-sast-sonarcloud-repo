pipeline {
    agent any
    tools {
        maven 'maven-3.9.6'
    }
    stages {
       	stage ( "Compile and Run Sonar Analysis" ) {
		steps {
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=buggywebapp13 -Dsonar.organization=buggywebapp13 -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=9e0049a2e2104bb3c7ebe4c7c4f773d6c83f9d24'
	         	}
	        	}
		}
    }
