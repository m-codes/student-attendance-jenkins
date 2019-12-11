pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                 sh 'mvn compile -f "/home/martin/Documents/gitHubRepos/student-attendance-jenkins"'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test -f "/home/martin/Documents/gitHubRepos/student-attendance-jenkins"'
            }
        }
    }
}
