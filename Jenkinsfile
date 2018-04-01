pipeline {
  agent {
    docker {
      image 'italktocomputers/concourse:ubuntu16.04_git'
    }
    
  }
  stages {
    stage('test1') {
      steps {
        sh 'ls -al'
      }
    }
  }
}