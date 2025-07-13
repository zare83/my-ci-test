pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git credentialsId: '3eb72975-204a-4257-af24-443e8a6c694f',
                    url: 'git@github.com:zare83/my-ci-test.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage running...'
            }
        }
    }
}
