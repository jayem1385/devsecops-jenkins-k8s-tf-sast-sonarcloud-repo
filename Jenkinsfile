pipeline {
    agent any
    tools {
        maven 'maven-3.9.6'
    }
    stages {
       	stage ( "Compile and Run Sonar Analysis" ) {
		steps {
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=cloudguru -Dsonar.organization=cloudguru -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=f6b0dcc8995fc63efeffb87cbdd76244650572ec'
	         	}
	        	}
		}
    }
