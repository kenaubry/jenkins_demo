pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                bat 'python app.py'
            }
        }
    }
}
