pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Starting Build Step'
        sh 'mvn clean install -Dlicense.skip=true'
        echo 'Build step complete'
      }
    }

  }
}