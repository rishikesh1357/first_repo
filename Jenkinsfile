pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git 'https://github.com/rishikesh1357/first_repo.git'
      }
    }
    stage('Run Python Script') {
      steps {
        sh 'python3 print.py'
      }
    }
  }
}
