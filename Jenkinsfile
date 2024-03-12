pipeline {
  agent {
    docker {
      image 'nginx'
      args 'web-1'
    }

  }
  stages {
    stage('') {
      steps {
        sh '''#!/bin/bash



apt update && apt upgrade -y
'''
      }
    }

  }
}