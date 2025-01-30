pipeline {
    agent any
    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning repository from GitHub...'
                git 'https://github.com/meer727/jenkins-pipeline-demo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
    }
}
