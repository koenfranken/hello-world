pipeline {
  agent {
    docker {
      image 'java:8'
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