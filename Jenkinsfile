pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        echo 'Dev Smoke Test'
      }
    }

    stage('QA') {
      steps {
        echo 'Sanity API test'
        echo 'Sanity UI test'
      }
    }

  }
}