pipeline {
  agent any
  stages {
    stage('Branch Detection') {
      steps {
        echo 'hello world'
        dir('DevOps') {
        git 'https://github.com/donbohman/devops.git'
        }
      }
    }
  }
}
