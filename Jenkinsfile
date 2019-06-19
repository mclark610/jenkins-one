pipeline {
    agent {
         docker {
	     image 'node:11.15.0-alpine'
	     args '-p3001:3000'
	 }
    }
    

    stages {
        stage('build') {
            steps {
	        sh 'echo "Starting npm version"'
		sh 'echo "Adding another line"'
		sh 'npm --version'
		sh 'ls -lrta'
            }
        }
    }
}
