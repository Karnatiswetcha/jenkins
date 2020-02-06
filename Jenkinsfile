pipeline {
    agent any
    stages {

        stage('Build2') {
            steps {
               sh 'echo "hello world"'
			   dir('Test1'){
            sh 'start.sh'
          }
			   
            }    
        }
    }
}