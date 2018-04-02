pipeline {
  agent {
    docker {
      image 'mavan:3.3.9-jdk-8'
      args 'https://github.com/SNivas12345/Postgres.git'
    }
    
  }
  stages {
    stage('intialize') {
      steps {
        echo 'Pipeline'
      }
    }
  }
}