pipeline {
  agent any
  stages {
    stage('Branch Detection') {
      steps {
        echo 'hello world'
        dir(path: 'DevOps') {
          git 'https://github.com/donbohman/devops.git'
          sh '. DevOps/echo.sh'
        }

      }
    }
  }
}