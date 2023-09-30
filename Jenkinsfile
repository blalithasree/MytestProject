pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
              echo "success"
            }
         stage('Compile') {
            steps {
              sh "mvn clean compile -Dskiptests=true"
            }  
        }
    }
}
