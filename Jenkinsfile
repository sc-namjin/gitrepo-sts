pipeline {
  agent any
  stages {
    stage('Source') {
      steps {
        git(url: 'https://github.com/sc-namjin/gitrepo-sts.git', branch: 'main', credentialsId: 'GitHub_Credential')
        dir(path: '/var/jenkins_home/workspace/gitrepo-sts_main')
      }
    }

  }
}