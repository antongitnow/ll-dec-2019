pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('checkout') {
            steps {
                checkout scm
            }
        }
	stage('build) {
            steps {
                sh 'python --version'
                sh 'python simple.py'
            }
	}
    }
}
