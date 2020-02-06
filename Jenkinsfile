pipeline {
    agent none
    stages {
        stage('build') {
            steps {
					node{

	dir("Test1"){
    		sh start.sh
	}
               docker ps
            }
        }
    }
	}
}
