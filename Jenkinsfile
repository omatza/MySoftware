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
                bat 'C:\\Xilinx\\Vivado\\2019.1\\tps\\win64\\python-2.7.5\\python.exe NewScreen.py'
			}
        }
    }
}