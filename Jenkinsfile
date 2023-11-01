pipeline {
  agent any
  stages {
    stage('Test1') {
      steps {
        git(url: 'https://github.com/pascariucosmin93/html.git', branch: 'main')
      }
    }

    stage('List') {
      steps {
        sh 'ls -la'
      }
    }

  }
}