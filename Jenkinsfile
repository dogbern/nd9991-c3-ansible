pipeline {
  agent any
  stages {
    stage('Install Nginx') {
      steps {
        ansiblePlaybook playbook: 'main.yaml', inventory: 'inventory'
      }
    }
  }
}