pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls -l'
                sh 'docker build -t harbor.asd/library/deneme:latest .'
                sh 'docker images'
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
