pipeline {
  agent {
    docker {
      image 'st-co_experiments:java-7'
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
        sh 'java HelloWorld'
      }
    }
  }
}
