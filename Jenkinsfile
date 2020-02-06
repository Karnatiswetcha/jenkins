pipeline {
    
    stages {
        stage('build') {
            steps {
	dir("C:\Program Files\Docker Toolbox"){
    		sh start.sh
	}
                sh 'npm --version'
            }
        }
    }
}
