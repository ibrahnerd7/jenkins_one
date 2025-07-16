pipeline {
agent { docker {image 'python:3.13.5-alpine3.22'}}

stages {
  stage('Build') {
    steps {
      echo 'Building ...'
    }
  }
  stage('Test') {
    steps {
      echo 'Testing ...'
    }
  }
  stage('Deploy') {
    steps {
      echo 'Deploying ....'
    }
  }
}

}
