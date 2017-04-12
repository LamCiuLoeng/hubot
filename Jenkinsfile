pipeline {
  agent any
  stages {
    stage('pull git') {
      steps {
        git(url: 'https://github.com/LamCiuLoeng/hubot.git', branch: 'master')
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