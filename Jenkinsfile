pipeline {
    agent none
    stages {
        stage('build') {
            steps {
	dir("Test1"){
    		start.sh
	}
                docker ps
            }
        }
    }
}
