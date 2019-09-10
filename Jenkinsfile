pipeline {
  agent {
    node {
      label 'cd-jenkins-slave'
    }

  }
  stages {
    stage('test') {
      agent {
        docker {
          image 'python36'
        }

      }
      steps {
        sh 'python -V'
      }
    }
  }
}