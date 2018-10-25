pipeline {
  agent { label 'linux' }
  stages {
    stage('checkout') {
      steps {
        git 'https://github.com/effectivejenkins/myProject.git'
      }
    }
    stage('Build') {
      steps {
        echo "Hello World"
      }
    }
  }
}
