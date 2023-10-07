pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://satobit@bitbucket.org/satobit/teste-pipeline.git')
      }
    }
    stage('Build') {
      steps {
        sh 'echo "Building..."'
      }
    }
    stage('Test') {
      steps {
        sh 'echo "Testing..."'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "Deploying..."'
      }
    }
  }
}
