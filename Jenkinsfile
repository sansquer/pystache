pipeline {
  agent any
  stages {
    stage('Run tests') {
      steps {
        sh './run_tests_with_coverage.sh'
      }
    }
  }
  environment {
    Test = 'Test'
  }
}