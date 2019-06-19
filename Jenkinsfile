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
    post {
        always {
	    echo 'This will always run'
	}
	success {
	    echo 'This will only run if successful'
	}
	failure {
	    echo 'This will run only if failed'
	}
	unstable {
	    echo 'This will run only if the run was marked as unstable'
	}
	changed {
	    echo 'This will run only if the state of the Pipeline has changed'
	    echo 'For example, if the pipeline was previously failing now ok'
	}

    }
}
