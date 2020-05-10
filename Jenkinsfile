pipeline {
   agent any

   stages {
      stage('Running addition') {
         sh './add_two_number 1 2'
         echo 'building form jenkin-pipeline..'
      }
      stage('Test') {
         steps {
            echo 'Testing form jenkin-pipeline..'
         }
      }
      stage('Deploy') {
         steps {
            echo 'Deploying form jenkin-pipeline..'
         }
      }
   }
}
