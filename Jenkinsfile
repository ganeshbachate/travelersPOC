pipeline {
  agent any
  stages {
  stage('Stage 1') {
      steps {
        script {
          echo 'Checkout'
          git branch: 'main', url: 'https://github.com/ganeshbachate/travelersPOC.git'
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
