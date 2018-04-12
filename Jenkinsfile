pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('mavenP') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}