pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        sh 'echo 123'
      }
    }
    stage('Install') {
      steps {
        sh 'python --version'
        sh 'env'
      }
    }
  }
  environment {
    python = '$PYTHON_ENVS'
  }
}