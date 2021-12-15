pipeline {
    agent any

    stages {
        stage('Build') {
            
            steps {
                sh 'mvn clean packages'
            }
        }
    }

    post {
        success {
            echo 'This will run only if successful'
        }
    }
}
