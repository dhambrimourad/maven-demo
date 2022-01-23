pipeline {
  agent any
  tools {
    maven 'maven-3.8.4'
    jdk 'jdk1.8'
  }
  stages {
    stage ('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}