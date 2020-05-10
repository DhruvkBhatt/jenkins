pipeline {
   agent any

   stages {
      stage('Changing permision') {
         steps{
            echo 'Changing form jenkin-pipeline..'
            sh 'chmod +x ./add_two_number'
         }
      }
      stage('Running') {
         steps {
            echo 'Runing the script form jenkin-pipeline..'
            sh './add_two_number 1 2'
         }
      }
      stage('Completed') {
         steps {
            echo 'completed addition of two number form jenkin-pipeline..'
         }
      }
   }
}
