pipeline {
    agent any 
    

    stages {
        stage('build') {
            steps {
	        sh 'echo "Starting npm version"'
                sh '/home/mclark/.nvm/versions/node/v11.10.1/bin/npm --version'
		sh 'ls -lrta'
            }
        }
    }
}
