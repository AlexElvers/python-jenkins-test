pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        sh '$python --version'
        sh 'env'
      }
    }
  }
  environment {
    python = '$PYTHON_ENVS'
  }
}