pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/Dharun-P-B/jenkinsqn3.git'
            }
        }

    stage('Build') {
        steps{
            bat  'python result.py'
        }
    }
  }
}

    
