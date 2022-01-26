pipeline {
    agent any

    stages {
        stage('npm build') {
            steps {
                bat 'npm install'
                bat 'npm start'
            }
        }
    }
}