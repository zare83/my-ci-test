pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git credentialsId: 'jenkins-ssh',
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
