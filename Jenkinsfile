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
      parallel {
        stage('build') {
          steps {
            echo 'hello build'
          }
        }

        stage('build-test') {
          steps {
            echo 'hello this is build test'
          }
        }

      }
    }

  }
}