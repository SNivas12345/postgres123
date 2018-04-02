pipeline {
  agent {
    docker {
      args 'https://github.com/SNivas12345/Postgres.git'
      image 'postgres'
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