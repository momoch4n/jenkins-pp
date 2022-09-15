pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "learning to build pipeline with Jenkinsfile"
                sh 'echo using shell within Jenkinsfile'
                echo 'not using shell in the Jenkinsfile'
            }
	}
	stage('test') {
	    steps {
	    	echo "testing 2nd stage duhhhh"
        }
    }
}
}
