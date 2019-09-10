pipeline {
  agent {
    node {
      label 'cd-jenkins-slave'
    }

  }
  stages {
    stage('test') {
      agent any
      environment {
        container = 'python36'
      }
      steps {
        sh 'python -V'
      }
    }
  }
}