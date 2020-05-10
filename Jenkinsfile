pipeline {
   agent any

   stages {
      stage('Compiling Java Code') {
         steps {
            echo 'compiling..'
            sh 'javac HelloWorld.java'
            
         }
      }
      stage('Running Java code') {
         steps {
            sh 'java HelloWorld'
            echo 'Running..'
         }
      }
   }
}
