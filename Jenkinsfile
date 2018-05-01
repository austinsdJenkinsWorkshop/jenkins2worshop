pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      parallel {
        stage('Say Hello') {
          steps {
            echo 'Hello World $MY_NAME'
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
  environment {
    MY_NAME = 'Greg'
  }
}