pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
	        sh 'echo "starting python"'
                sh 'python --version'
		sh '''
		  echo "This is a multiline shell in "
		  echo "the file."
		  echo "ls -lah"
		'''
            }
        }
    }
}
