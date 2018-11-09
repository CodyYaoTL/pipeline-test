pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'hello world'
            }
        }
    }
    post {
    	always {
    		echo 'Completed Deployment'
    	}
    }
}