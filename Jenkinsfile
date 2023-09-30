pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/Md-Sadaf/curriculum-app', branch: 'dev')
        waitForBuild 'fir'
      }
    }

  }
}