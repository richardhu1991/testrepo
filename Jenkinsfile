pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd
ls -al
echo build'''
      }
    }

    stage('test') {
      steps {
        sh 'echo test'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo deploy'
      }
    }

  }
}