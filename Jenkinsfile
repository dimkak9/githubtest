pipeline {
agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/dimkak9/githubtest.git'
            }
        }
        stage('build') {
            steps {
                bat 'python 1.py'
            }

        }
    }
}