pipeline {
  agent any
  stages {
    stage('Branch Detection') {
      steps {
        echo 'hello world'
        dir(path: 'DevOps') {
          git 'https://github.com/donbohman/devops.git'
          bat(script: 'echo1.sh', returnStatus: true)
        }

      }
    }
  }
}