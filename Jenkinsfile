pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh '''pwd
ls'''
      }
    }

    stage('stage 2') {
      steps {
        echo 'this is stage 2'
      }
    }

    stage('stage  3') {
      steps {
        echo 'stage 3'
      }
    }

    stage('final') {
      steps {
        sh 'ls'
      }
    }

  }
}