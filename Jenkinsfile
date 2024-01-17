pipeline {
  agent {
    node {
      label 'test-agent-a10'
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