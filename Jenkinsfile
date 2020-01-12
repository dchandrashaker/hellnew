node('node1')
pipeline {
  agent { dockerfile true }
  stages {
    stage('Build') {
      steps {
	docker.build '-t bulletinboard:1.0 .'
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
