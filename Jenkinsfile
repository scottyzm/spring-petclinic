pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn -B clean install'
      }
    }

  }
}