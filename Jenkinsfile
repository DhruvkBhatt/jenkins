pipeline {
   agent any

   stages {
      stage('Build') {
         steps {
            echo 'building..'
            sh 'javac HelloWorld.java'
            sh 'java HelloWorld'
         }
      }
      stage('Test') {
         steps {
            echo 'Testing..'
         }
      }
      stage('Deploy') {
         steps {
            echo 'Deploying..'
         }
      }
   }
}
