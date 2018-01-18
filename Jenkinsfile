pipeline {
  agent {
    docker {
      image 'rb-dtr.de.bosch.com/st-co/st-co_experiments:java-7'
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