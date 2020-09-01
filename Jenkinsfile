pipeline {
  agent any
  stages {
    stage('stage-1') {
      steps {
        sh 'echo "Hello from Jenkins $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1.0'
  }
}
