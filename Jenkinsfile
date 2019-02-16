pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'building..'
checkout scm
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}