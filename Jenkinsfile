pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'ls -l'
                sh 'docker build -t harbor.asd.com/library/komki:latest .'
                sh 'docker run -d -p 8989:80 --name nginx harbor.asd.com/library/komki:latest '
            }
        }
    }
}
