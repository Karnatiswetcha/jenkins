pipeline {
    agent none
    stages {
        stage('build') {
            steps {
			sh start.sh
			docker ps
            }
        }
    }
}
