pipeline {
  agent any
  stages {
    stage('pull git') {
      steps {
        echo 'pull repo'
      }
    }
    stage('build') {
      steps {
        build 'hubot'
        echo 'build hubot'
      }
    }
    stage('done') {
      steps {
        echo 'done'
      }
    }
  }
}