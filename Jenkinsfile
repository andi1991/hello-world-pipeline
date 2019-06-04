pipeline {
        agent {
		label 'server'
	}
        tools {
        maven 'mvn3.5.4'
        }

        stages{
        	stage('Build'){
        		steps {
                                echo "ruier is success"
        			sh "mvn clean package"
        			sh "printenv"

        		}
        	}
        }
}
