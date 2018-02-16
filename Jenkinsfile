pipeline {
  agent any
  stages {
    stage('Clear Workspace') {
      steps {
        sh './gradlew clean'
      }
    }
    stage('Run Unit Tests') {
      steps {
        sh '''./gradlew testRelease
'''
      }
    }
  }
}