pipeline {
  agent any
  stages {
    stage('List Files') {
      steps {
        bat '''
                C:
                cd \\
                dir
                '''
      }
    }

    stage('DataFactory') {
      steps {
        bat 'dir'
      }
    }

  }
}