pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building...'
        powershell 'node -v'
        powershell 'node app.js'
      }
    }
  }
}
