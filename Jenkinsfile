pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/venkat0007/subrataction_1.git', branch: 'master', credentialsId: 'venkat0007')
      }
    }
  }
}