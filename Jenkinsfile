pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        sh 'mvn install'
      }
    }
    stage('Message') {
      steps {
        echo 'Done'
      }
    }
    stage('test') {
      steps {
        sh 'mvn test'
      }
    }
    stage('done') {
      steps {
        echo 'done doen'
      }
    }
  }
}