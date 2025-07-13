pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/YourUsername/my-ci-test.git'
            }
        }
        stage('Build') {
            steps {
                echo '✅ Jenkins اجرا شد! Webhook کار کرد!'
            }
        }
    }
}