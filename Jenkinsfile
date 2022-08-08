pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git(url: 'https://github.com/sc-namjin/gitrepo-sts.git', branch: 'main', credentialsId: 'namjinpark')
      }
    }

  }
}