pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'ls -l'
                sh 'docker build -t harbor.asd.com/library/komki:latest .'
            }
        }
    }
}
