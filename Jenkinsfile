pipeline {
  agent {
    docker {
      image 'italktocomputers/concourse:ubuntu16.04_python3'
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