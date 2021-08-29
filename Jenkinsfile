pipeline {
   agent {
      docker {
         sh 'python --version'
         image 'python:3.9.6'
      }
   }
   stages {
      stage('Build') {
         steps {
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