pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello Blue Ocean"'
      }
    }

    stage('Test') {
      steps {
        archiveArtifacts 'release'
      }
    }

  }
}