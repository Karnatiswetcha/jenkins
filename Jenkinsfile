pipeline {
    agent none
    stages {
	node{
        stage('build') {
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
