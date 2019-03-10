

pipeline {
    agent any 
    stages {
        stage('clean') { 
            steps {
                // bat "git clone https://github.com/shungchen03/my-app.git" 
                // bat "C:\\apache-maven-3.6.0\\bin\\mvn clean -f my-app"
                bat "echo AA"
            }
        }
        stage('Test') { 
            steps {
                bat "C:\\apache-maven-3.6.0\\bin\\mvn test"
            }
        }
        stage('Deploy') { 
            steps {
                bat "C:\\apache-maven-3.6.0\\bin\\mvn package"
            }
        }
    }
}