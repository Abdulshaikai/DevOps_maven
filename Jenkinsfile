pipeline {
  agent any
    tools {
        maven 'Maven 3.6.0'
        jdk 'jdk10'
    }
  stages {
    stage ('build stage') {
      steps {
          echo "hello! world"
           echo "PATH = ${PATH}"
           echo "M2_HOME = ${M2_HOME}"

         }
    }
  }
}
