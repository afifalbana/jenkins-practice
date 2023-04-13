pipeline {
  agent {
    node {
      label 'jenkins-slave'
    }

  }
  stages {
    stage('Run CMD: Check me out') {
      steps {
        sh 'hostname'
        sh 'whoami'
        sh 'ip a | grep global'
      }
    }

    stage('Run CMD: Update APT') {
      steps {
        sh 'which ansible'
      }
    }

  }
}