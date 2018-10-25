pipeline {
  agent { label 'linux' }
  stages {
    stage('checkout') {
      steps {
        git 'https://github.com/louiekwan/project_pipline.git'
      }
    }
    stage('Build') {
      steps {
        echo "Hello World"
      }
    }
  }
}
