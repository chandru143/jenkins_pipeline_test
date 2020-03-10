pipeline {
   agent any
    stages {
       stage("one") {
         steps{
          echo "Welcome Chandra"
         }
       }
       stage("two") {
        input {
         echo "are you sure, DO you want to continue"
        }
        steps{
          echo "welcome come to stage two"
        }
       }
  }
}
