pipeline {
     
     agent any
     
     stages {
         
         stage('build') {
             steps {
                 echo 'Building...'
             }
         }
          
         stage('deploy to dev') {
             steps {
                 echo 'Deploying to DEV .....'
             }
         }

         stage('deploy to test') {
             steps {
                 echo 'Deploying...'
             }
         }
        
         stage('deploy to staging') {
             steps {
                 echo 'Deploying...'
             }
         }

         stage('deploy to prod') {
             when {
                branch 'master'
             }              
             steps {
                 echo 'Deploying...'
             }
         }
     }
 }
