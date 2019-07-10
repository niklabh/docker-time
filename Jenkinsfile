pipeline {
  agent any
  stages {
    stage('') {
      steps {
        git(url: 'https://github.com/niklabh/docker-time', branch: 'master')
      }
    }
    stage('check') {
      steps {
        sh 'git branch -a'
      }
    }
  }
}