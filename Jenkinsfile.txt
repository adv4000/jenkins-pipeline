pipeline {
    agent any

    stages {
        stage('My-JenkinsBuild-Steps') {
            steps {
               echo "Start"
               echo "Doing something.."
               echo "End"
            }
        }
    }
}

