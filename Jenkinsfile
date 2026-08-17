pipeline {
    agent any
    stages {
        stage('Build') {
            steps { 
                // On Windows, use 'bat' instead of 'sh'
                bat 'python -m pip install pytest' 
            }
        }
        stage('Test') {
            steps { 
                bat 'python -m pytest' 
            }
        }
    }
}