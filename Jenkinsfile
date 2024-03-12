pipeline {
  agent any
  stages {
    stage('api') {
      steps {
        sh '''cd api
docker build -t new-api .'''
      }
    }

  }
}