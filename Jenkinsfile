pipeline {
  agent {
    docker {
      image 'maven:3.8.1-adoptopenjdk-11'
      args 'mvn -B -DskipTests clean package'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }

  }
}