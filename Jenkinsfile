pipeline {
  agent any
  stages {
    stage('Say Hello') {
      parallel {
        stage('Say Hello') {
          steps {
            echo 'Hello World!'
          }
        }
        stage('javaVersion') {
          steps {
            sh 'java -version'
          }
        }
      }
    }
  }
}