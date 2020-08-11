pipeline {
    agent any


    stages {
        stage('Clone') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/omatza/MySoftware.git'
            }
		}

        stage('Build') {
            steps {
                // Run python on windows agent.
                bat 'python NewScreen.py'
			}
        }
    }
}