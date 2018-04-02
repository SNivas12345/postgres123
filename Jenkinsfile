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
    stage('Build') {
      steps {
        sh '''stages {
            stage(\'Build\') {
                steps {
                    echo \'This is the Build Stage\'
                }
            }'''
        }
      }
      stage('Test') {
        steps {
          sh '''stage(\'Test\') {
                steps {
                    echo \'This is the Testing Stage\'
                }
            }'''
          }
        }
        stage('Deploy') {
          steps {
            echo 'Deploy'
            sh '''stage(\'Deploy\') {
                steps {
                    echo \'This is the Deploy Stage\'
                }
            }'''
            }
          }
        }
      }