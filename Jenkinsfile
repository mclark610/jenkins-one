pipeline {
    agent any
    stages {
        stage('build') {
            steps {
	        sh 'echo "starting something"'
		sh '''
		  echo "This is a multiline shell in "
		  echo "the file."
		  echo "ls -lah"
		'''
            }
        }
    }
}
