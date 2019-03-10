

pipeline {
    agent any 
    stages {
        stage('clean') { 
            steps {
                // bat "git clone https://github.com/shungchen03/my-app.git" 
                bat "C:\\apache-maven-3.6.0\\bin\\mvn clean"
                bat "echo AA"
            }
        }
        stage('Test') { 
            steps {
                // bat "C:\\apache-maven-3.6.0\\bin\\mvn test"
				bat "echo BB"
            }
        }
        stage('Deploy') { 
            steps {
                bat "C:\\apache-maven-3.6.0\\bin\\mvn package"
            }
        }
    }
}