pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/lavakush07/curriculum-app.git', branch: 'dev')
      }
    }

    stage('testing') {
      steps {
        sh '''ls -la
echo "Hello Lavakush"'''
        sh 'ls -la'
      }
    }

  }
}