pipeline {
  agent {
    dockerfile {
      filename 'index'
    }

  }
  stages {
    stage('Test1') {
      steps {
        git(url: 'https://github.com/pascariucosmin93/html.git', branch: 'main')
      }
    }

  }
}