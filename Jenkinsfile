pipeline {
  agent any
  stages {
    stage('Source') {
      parallel {
        stage('Source') {
          steps {
            git(url: 'https://github.com/sc-namjin/gitrepo-sts.git', branch: 'main', credentialsId: 'GitHub_Credential')
          }
        }

        stage('working dir') {
          steps {
            dir(path: '/var/jenkins_home/workspace/gitrepo-sts_main/config')
          }
        }

      }
    }

  }
}