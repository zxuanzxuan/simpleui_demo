pipeline {
  agent {
    node {
      label 'cd-jenkins-slave'
    }

  }
  stages {
    stage('test') {
      agent {
        node {
          label 'python36'
        }

      }
      steps {
        sh 'python -V'
      }
    }
  }
}