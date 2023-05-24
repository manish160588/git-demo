pipeline {
  agent any
  stages {
    stage('sdas') {
      steps {
        junit(testResults: 'target/**', skipOldReports: true)
      }
    }

  }
}