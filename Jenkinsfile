pipeline {
  agent any

  tools {
    maven 'Maven3'   // Jenkins -> Global Tools -> Name should be Maven3
  }

  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/suchitayerkar30/SpringBootWebApp-project.git'
      }
    }

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
