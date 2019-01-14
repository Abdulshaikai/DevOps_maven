pipeline {
  agent any
  tools {
        maven 'apache-maven-3.5.3'
    }
  stages {
    stage ('build stage') {
      steps {
          sh 'mvn clean compile'

         }
    }
  }
}
