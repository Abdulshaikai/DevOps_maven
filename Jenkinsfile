pipeline {
  agent any
  stages {
    stage ('build stage') {
      steps {
           withMaven(jdk: 'JAVA_HOME', maven: 'M2_HOME') {
               mvn install
           }

         }
    }
  }
}
