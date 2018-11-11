pipeline {
  agent any
  stages {
    stage('Get a file') {
      environment {
        FILE = 'p1.txt'
      }
      steps {
        readFile(file: '${FILE}', encoding: 'UTF-8')
      }
    }
  }
  environment {
    FILE = 'p1.txt'
  }
}