pipeline {
  agent any
  stages {
  stage('Checkout') {
      steps {
        script {
          checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/ganeshbachate/travelersPOC.git']])
        }
      }
    }
  stage('Build PythonCode') {
      steps {
        script {
          echo 'Stage 2'
        }
      }
    }
  }
}
