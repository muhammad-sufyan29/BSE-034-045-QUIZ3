pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Run the Python code
               bat 'python.py'
            }
        }
        stage('Run') {
            steps {
               bat 'python'
            }
        }
    }
}
