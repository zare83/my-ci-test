pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'git@github.com:zare83/my-ci-test.git'
            }
        }
        stage('Build') {
            steps {
                echo '✅ Jenkins اجرا شد! Webhook کار کرد!'
            }
        }
    }
}
