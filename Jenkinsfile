pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                 bat 'mvn clean -f "/home/martin/Documents/gitHubRepos/student-attendance-jenkins"'
                 bat 'mvn compile -f "/home/martin/Documents/gitHubRepos/student-attendance-jenkins"'
            }
        }
        stage('Test') {
            steps {
                bat 'mvn test -f "/home/martin/Documents/gitHubRepos/student-attendance-jenkins"'
            }
        }
    }
}
