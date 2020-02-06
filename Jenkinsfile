pipeline {
    agent none
    stages {
        stage('build') {
		node{
            steps {
	dir("Test1"){
    		sh start.sh
	}
               docker ps
            }
        }
    }
	}
}
