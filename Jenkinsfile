pipeline {
  agent {
    docker {
      image 'java:7'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'javac HelloWorld.java'
      }
    }
    stage('test') {
      steps {
        sh 'java HelloWorld'
      }
    }
  }
}