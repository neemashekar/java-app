pipeline {
  agent any
  stages {
    stage('nonsense') {
      steps {
        echo 'hello world'
      }
    }
    stage('build') {
      steps {
        sh 'mvn clean package -DskipTests'
      }
    }
  }
}