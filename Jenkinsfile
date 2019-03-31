pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'g++ sample.cpp -o sample && ./sample'
            }
        }
    }
}