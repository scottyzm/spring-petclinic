pipeline {
  agent {
    docker {
      image 'jenkins/ssh-agent:latest-jdk11'
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