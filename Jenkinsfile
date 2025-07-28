pipeline {
    agent any

    stages {
        stage('Git Clone') {
            steps {
                git url: 'https://github.com/salmasulthana2010/public-jenkins.git', branch: 'main'
            }
        }

        stage('List Files') {
            steps {
                sh 'ls -l'
            }
        }

        stage('Build & Test') {
            steps {
                sh 'echo "Build and Test completed"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'cat file1'
            }
        }
    }
}
