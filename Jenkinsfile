pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo \'hello, world\''
      }
    }

    stage('Test') {
      steps {
        echo 'hello'
      }
    }

    stage('') {
      steps {
        build 'gitstudy'
      }
    }

  }
}