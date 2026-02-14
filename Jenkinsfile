pipeline {
    agent any

    stages {

        stage('Install Dependencies') {
            steps {
                bat 'pip install -r requirements.txt'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage executed successfully!'
            }
        }

        stage('Success Message') {
            steps {
                echo 'Pipeline executed successfully!'
            }
        }
    }
}
