pipeline {
    agent {
	docker {
	    label 'my-defined-label'
	    image 'php:8.1.0-alpine'
	}
    }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
