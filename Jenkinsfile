pipeline {
   agent any
    stages {
       stage("one") {
         steps{
          echo "Welcome Chandra"
         }
       }
       stage("two") {
        steps{
          input "are you sure, DO you want to continue"
          echo "welcome come to stage two"
        }
       }
       stage("three") {
          when {
             not {
               branch "master"
             }
            }
          steps {
           echo "welcome to steps 3"  
          }
       }
  }
}
