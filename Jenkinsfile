pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/BorhenCherif/DevOps-Pipeline-Project.git', branch: 'master')
      }
    }

    stage('build') {
      steps {
        echo 'building'
      }
    }

  }
}