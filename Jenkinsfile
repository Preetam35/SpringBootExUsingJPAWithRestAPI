pipeline {
    //agent any
	agent {docker { image 'maven:3.8.4'} }
    stages {
        stage('Hello') {
            steps {
				sh 'mvn --version'
                echo 'Hello World'
            }
        }
		stage('Build') {
            steps {
                echo 'Build Application'
            }
        }
		 stage('Test') {
            steps {
                echo 'Test Application'
            }
        }
		 stage('Deploy') {
            steps {
                echo 'Deploy Application'
            }
        }
    }
	
}
