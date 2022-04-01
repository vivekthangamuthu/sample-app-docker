pipeline {
    agent any

    stages {
        stage('Source') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/vivekthangamuthu/sample-app-docker.git'
            }

        }
        stage('Build') {
            steps {
                // Docker Build
                sh 'docker build -t sampleapp .'
            }

        }
    }
}
