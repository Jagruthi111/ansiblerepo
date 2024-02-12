pipeline{
  agent java
  stages {
    stage('checkout stage') {
      steps {
        sh 'rm -rf ansiblerepo'
        sh 'git clone '
      }
    }
    stage('Invoke playbook')  {
          steps {
        sh 'ansible-playbook -i hosts demo.yml'
      }
  }
  }
}
        
