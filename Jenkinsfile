pipeline {
  agent any
  stages {
    stage('check out code') {
      steps {
        git(url: 'https://github.com/djamara/TestNodeJenkins', branch: 'main')
      }
    }

  }
}