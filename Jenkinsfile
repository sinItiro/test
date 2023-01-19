pipeline {
  agent any
  stages {
    stage('sleep') {
      steps {
        sleep 5
      }
    }

    stage('allocate') {
      steps {
        node(label: 'node') {
          echo 'asdfasdf'
        }

      }
    }

  }
}