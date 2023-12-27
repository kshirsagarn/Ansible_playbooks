pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'pwd'
      }
    }

    stage('Test') {
      steps {
        echo 'hello'
      }
    }

    stage('Deploy to test') {
      parallel {
        stage('Deploy to test') {
          steps {
            sh 'ls'
          }
        }

        stage('Deploy to Prod') {
          steps {
            echo 'pwd'
          }
        }

      }
    }

  }
}