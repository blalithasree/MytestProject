pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
               git credentialsId: '9b9243e7-6148-4e01-8f99-9922bfd53b4a', url: 'https://github.com/blalithasree/MytestProject.git'
            }
        }
    }
}
