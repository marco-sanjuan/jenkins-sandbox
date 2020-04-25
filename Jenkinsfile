pipeline {
  agent any
  stages {
    stage('Stage 1') {
      steps {
        echo 'Hello'
        git(url: 'https://github.com/marco-sanjuan/kubernetes-sandbox/', branch: 'master')
      }
    }
  }
}