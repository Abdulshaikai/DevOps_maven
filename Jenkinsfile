pipeline {
  agent any
  tools {
        maven 'maven-3.5.3'
    }
  stages {
    stage ('build stage') {
      steps {
          sh 'mvn clean compile'

         }
    }
  }
}
