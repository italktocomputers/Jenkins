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
  }
  environment {
    ENV = 'DEV'
  }
}