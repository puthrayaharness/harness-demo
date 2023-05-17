pipeline {
   agent any
   parameters {
     string(name: 'STATEMENT', defaultValue: 'hello; ls /', description: 'What should I say?')
   }
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact"
               """
           }
       }
      stage('Deploy Code') {
          steps {
               sh """
               echo "Deploying Code"
               """
          }
      }
   }
}
