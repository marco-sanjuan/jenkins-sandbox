pipeline {
  agent any
  stages {
    stage('Git Checkout') {
      steps {
        echo 'Checkout from GitHub'
        git(url: 'https://github.com/marco-sanjuan/kubernetes-sandbox/', branch: 'master')
      }
    }
  }
}