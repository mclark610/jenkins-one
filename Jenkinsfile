pipeline {
    #agent { docker { image 'node:11.10.1' } }
    stages {
        stage('build') {
            steps {
	        sh 'echo "Starting npm version"'
                sh 'npm --version'
		sh 'ls -lrta'
            }
        }
    }
}
