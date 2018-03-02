pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        parallel(
          "Install": {
            sh '$python --version'
            sh 'env'
            
          },
          "foo": {
            sh 'echo 123'
            
          }
        )
      }
    }
  }
  environment {
    python = "$PYTHON_ENVS/test/bin/python"
  }
}