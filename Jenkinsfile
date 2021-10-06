pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        sh '''git checkout main
git fetch 
git merge main branch_staging'''
      }
    }

  }
}