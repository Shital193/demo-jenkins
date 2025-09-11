// Jenkinsfile (declarative)
pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        echo "Checking out repository..."
        // "checkout scm" will use the repo that triggered the build
        checkout scm
      }
    }

    stage('Build') {
      steps {
        echo "Building..."
        sh 'echo build step: listing files; ls -la'
      }
    }

    stage('Test') {
      steps {
        echo "Running tests (demo)..."
        sh 'echo tests passed'
      }
    }
  }
}
