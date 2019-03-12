pipeline {
  agent {
    node {
      label 'my-defined-label'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}