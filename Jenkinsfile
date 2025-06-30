pipeline {
  agent any

  tools {
    maven 'Maven3'
  }

  stages {
    stage('Build') {
      steps {
        sh 'mvn clean package'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployment steps will go here.'
      }
    }
  }
}

