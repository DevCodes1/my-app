pipeline {
    agent any
    stages {
        stage('mvm clean') {
            steps {
                 bat "mvn clean"
            }
        }
        stage('Test') {
            steps {
                bat "mvn test"
            }
        }
        stage('Deploy') {
            steps {
                bat "mvn package"
            }
        }
    }
}
   
