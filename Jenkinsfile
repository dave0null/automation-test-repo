pipeline {
    agent any 
    parameters {
	string(name: 'STATEMENT', defaultValue: 'hello; ls /', description: 'What should I say?')
    }
    stages {
        stage('Example') {
	    steps {
		sh("echo ${STATEMENT}")
	    }
	}
    }
}
