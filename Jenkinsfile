pipeline {
  agent any
  stages {
    stage('first-jenkins-msg') {
      parallel {
        stage('first-jenkins-msg') {
          steps {
            echo 'my first jenkins msg'
          }
        }

        stage('shell') {
          steps {
            sh 'pwd'
          }
        }

      }
    }

  }
}