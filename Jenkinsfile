pipeline {
    agent any
    tools {
        maven 'maven-3.9.6'
    }
    stages {
       	stage ( "Compile and Run Sonar Analysis" ) {
		steps {
		sh 'mvn clean verify sonar:sonar -Dsonar.projectKey=myproject-devsecops -Dsonar.organization=myproject-devsecops -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=f2e1f422a7d32b243c79e703c1bd4861b6acb4e0'
	         	}
	        	}
		}
    }
