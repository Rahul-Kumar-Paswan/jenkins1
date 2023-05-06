pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''ls
pwd
date
'''
      }
    }

    stage('build') {
      steps {
        echo 'hello build'
      }
    }

  }
}