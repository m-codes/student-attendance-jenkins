pipeline {
    agent any
    stages {
        stage('Fetch') {
            steps {
                sh 'git clone "https://github.com/m-codes/student-attendance-jenkins.git"'
            }
        }
        stage('Build') {
            steps {
                 sh 'mvn clean -f "/home/martin/Documents/gitHubRepos/student-attendance-jenkins"'
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
