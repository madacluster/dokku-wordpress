pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh '''export WORDPRESS_VERSION=3.7.16

make build APP_NAME=blog SERVER_NAME=dokku.me'''
      }
    }
  }
}