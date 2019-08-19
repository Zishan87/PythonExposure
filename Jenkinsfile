node ('python') {

  stage 'Checkout'
  checkout scm
  gitCommit = bat(returnStdout: true, script: 'git rev-parse HEAD').trim()
  shortCommit = gitCommit.take(6)
  stage 'Build'
  bat 'python --version'
    }