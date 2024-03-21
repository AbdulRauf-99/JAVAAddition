pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Checkout the code from Git repository
                git 'https://github.com/your/repository.git'
                // Build the code using Maven
                sh 'mvn clean install'
            }
        }
    }
}
