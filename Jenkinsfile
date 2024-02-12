pipeline {
  agent any
  stages {
    stage('checkout stage') {
      steps {
        sh 'rm -rf ansiblerepo'
        sh 'git clone https://github.com/Jagruthi111/ansiblerepo.git'
      }
    }
    stage('running playbook') {
      steps {
        sh 'ansible-playbook -i hosts demo.yml'
      }
    }
  }
}
