pipeline {
  agent {
    docker {
      image 'java:7'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'javac JavaHelloWorld.java'
      }
    }
    stage('test') {
      steps {
        sh 'java JavaHelloWorld'
      }
    }
  }
}