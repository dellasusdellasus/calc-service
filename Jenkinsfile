pipeline {
  agent any
  stages {
    stage('Code') {
      steps {
        git 'https://github.com/mypractice96/calc-service'
      }
    }
    stage('Build') {
      steps {
        sh 'mvn clean install'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "Deploy"'
      }
    }
  }
}