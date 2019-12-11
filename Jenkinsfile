

node {

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}

// node {
//     stage('Fetch') {
//       git url: 'https://github.com/m-codes/student-attendance-jenkins.git'
//     }
   
//   stage('Build') {
//         bat '''
//         cd /home/martin/Documents/gitHubRepos
//         javac -cp "C:\\Users\\Jakub\\.p2\\pool\\plugins\\org.junit_4.12.0.v201504281640\\junit.jar";"C:\\Users\\Jakub\\.p2\\pool\\plugins\\org.hamcrest.core_1.3.0.v201303031735.jar";. "Student.java" "studentTest.java"
//         '''
//   }
  
//   stage('Test') {
//         bat '''
//         cd %WORKSPACE%\\studentAttendance\\src\\
//         java -cp "C:\\Users\\Jakub\\.p2\\pool\\plugins\\org.junit_4.12.0.v201504281640\\junit.jar";"C:\\Users\\Jakub\\.p2\\pool\\plugins\\org.hamcrest.core_1.3.0.v201303031735.jar";. org.junit.runner.JUnitCore "studentTest"
//         '''
//   }
// }
