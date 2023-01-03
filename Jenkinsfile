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
        archiveArtifacts artifacts: '*.txt', fingerprint: true, followSymlinks: false, onlyIfSuccessful: true
      }
    }

  }
}
