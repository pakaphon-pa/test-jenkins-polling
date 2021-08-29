pipeline {
   agent { docker 'python:3.9.6' }
   stages {
      stage('Build') {
         steps {
            sh 'python -v'
            echo 'BUILD'
         }
      }
      stage('Test') {
         steps {
            echo 'TEST'
         }
      }
      stage('Deploy') {
         steps {
            echo 'DEPLOYYYYYYY'
         }
      }
   }
}