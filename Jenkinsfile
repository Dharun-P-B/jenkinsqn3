pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git 'https://github.com/Dharun-P-B/jenkinsqn3.git'
            }
        }

        stage('Build') {
            steps {
                bat '"C:\\Users\\dharu_naut31y\\AppData\\Local\\Python\\bin\\python.exe" result.py'
            }
        }
    }
}

    
