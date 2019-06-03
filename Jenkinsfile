pipeline {
        agent any
        tools {
        maven 'mvn3.5.4'
        }

        stages{
        	stage('Build'){
        		steps {
        			sh "mvn clean package"
        			sh "printenv"
        		}
        	}
        }
}
