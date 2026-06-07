pipeline {

    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Pulling latest code...'
            }
        }

        stage('Build & Test') {
            steps {
                bat 'mvn clean test'
            }
        }

    }

}
