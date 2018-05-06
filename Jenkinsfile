pipeline {
  agent any
  stages {
    stage ('build stage') {
      steps {
        withMaven (maven: 'maven_3_5_3'){
           sh 'mvn clean compile'
            }
         }
    }
  }
}
