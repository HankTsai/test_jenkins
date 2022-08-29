pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sh '''asd="123456789"
echo ${asd} > test.csv

                '''
          }
        }

        stage('sleep') {
          steps {
            sleep 10
          }
        }

      }
    }

  }
}