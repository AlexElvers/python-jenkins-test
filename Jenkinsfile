pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        checkout scm
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
