pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git credentialsId: 'd69e0610-4535-451f-a874-c62b6a30a9ae',
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
