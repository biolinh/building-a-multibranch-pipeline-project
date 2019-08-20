pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo "Hello world!"'
          }
        }
        stage('') {
          steps {
            sh 'echo "scan sonar"'
          }
        }
      }
    }
    stage('build release') {
      steps {
        sh '''echo Release
'''
      }
    }
    stage('Build master') {
      steps {
        sh 'Build master'
      }
    }
  }
}