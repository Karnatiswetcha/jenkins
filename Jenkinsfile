pipeline {
    agent none
node{
    stages {
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
