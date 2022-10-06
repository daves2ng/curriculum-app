pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/daves2ng/curriculum-app', branch: 'dev')
      }
    }

    stage('Logs') {
      steps {
        sh 'ls -la'
      }
    }

  }
}