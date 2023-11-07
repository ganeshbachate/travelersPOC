pipeline {
  agent any
  stages {
  stage('Stage 1') {
      steps {
        script {
          echo 'Checkout'
          checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/ganeshbachate/travelersPOC.git']])
        }
      }
    }
  stage('Stage 2') {
      steps {
        script {
          echo 'Stage 2'
        }
      }
    }
  }
}
