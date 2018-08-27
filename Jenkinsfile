pipeline {
  agent {
    docker {
      image 'python'
      args 'test.py'
    }
    
  }
  stages {
    stage('test1') {
      steps {
        sh 'ls -al'
      }
    }
    stage('test2') {
      steps {
        sh 'python3 test.py'
      }
    }
  }
  environment {
    ENV = 'DEV'
  }
}