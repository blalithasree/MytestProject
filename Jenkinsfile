pipeline {
    agent any
    tools{
        jdk "jdk11"
        maven "maven3"
    }
    stages {
        stage('Git Checkout') {
            steps {
              echo "success"
            }
        }
         stage('Compile') {
            steps {
              sh "mvn clean compile -DskipTests=true"
            }  
        }
    }
}
