pipeline {
  agent { dockerfile true }
  stages {
    stage('Build') {
      steps {
        docker 'build -t nginx_image .'
      }
    }

    stage('Test') {
      steps {
        echo 'TestStage'
      }
    }

    stage('Depoy') {
      steps {
        echo 'DeployStage'
      }
    }

  }
}
