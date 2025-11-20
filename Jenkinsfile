pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Tests') {
            steps {
                echo 'Running tests...'
                bat 'run-tests.bat'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished.'
        }
    }
}
