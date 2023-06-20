pipeline {
   agent any
   options {
      timestamps()
   } 
   environment {
      OWNER = 'Yurii'
   }
    
   stages {
   
      stage("Build") {
          steps {
            echo 'Jenkins makes a build'
         }
      }
      
      stage("Tests") {
          steps {
            echo 'Jenkins makes a tests'
         }
      }

      stage("Deploy") {
          steps {
            echo 'Deploy was successful'
          }

      }  
   }
}