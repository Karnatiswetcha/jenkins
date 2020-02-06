pipeline {
    agent none
    stages {
        stage('build') {
            steps {
	dir("Test1"){
    		sh start.sh
	}
                sh 'npm --version'
            }
        }
    }
}
