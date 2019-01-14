pipeline {
  agent any
  tools {
        jdk 'jdk-1.7.0_131'
        maven 'maven-3.5.0'
    }
  stages {
    stage ('build stage') {
      steps {
          sh 'mvn clean compile'

         }
    }
  }
}
