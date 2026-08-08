pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning repository'
                git branch:'main', url:'https://github.com/siddhi3022/rrrr.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application'
            }
        }
    }
}
