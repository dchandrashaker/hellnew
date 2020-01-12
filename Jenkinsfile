pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo helo world'
      }
    }

    stage('test') {
      steps {
        sh 'deploy'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo "hello"'
      }
    }

  }
}