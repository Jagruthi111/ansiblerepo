pipeline {
  agent any
  stages {
    stage('checkout stage') {
      steps {
        sh 'rm -rf GrafanaRepo'
        sh 'git clone '
      }
    }
    stage('running playbook') {
      steps {
        sh 'ansible-playbook -i hosts demo.yml'
      }
    }
  }
}
